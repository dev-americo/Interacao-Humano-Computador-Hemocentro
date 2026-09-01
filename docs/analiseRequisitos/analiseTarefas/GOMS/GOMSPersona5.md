## Introdução

O [GOMS](#ref1) é um método de análise de tarefas em Interação Humano-Computador focado em descrever o comportamento de **usuários competentes**, ou seja, aqueles que já dominam as rotinas do sistema e não cometem erros. 

A interação é estruturada em 4 componentes básicos:

- **Objetivos (*Goals*):** O que o usuário deseja realizar no sistema.
- **Operadores (*Operators*):** As ações físicas (como clicar ou teclar) e cognitivas (mentais) necessárias.
- **Métodos (*Methods*):** A sequência exata de passos e operadores para se atingir um objetivo.
- **Regras de Seleção (*Selection Rules*):** A decisão do usuário sobre qual método escolher quando o sistema oferece mais de um caminho para o mesmo objetivo.

## Analise GOMS - Emitir a Carteirinha de Identificação

Abaixo segue a análise GOMS

```
GOAL 0: Emitir a carteirinha de identificação integrada com a solicitação do laudo de fenotipagem sanguínea
  
  GOAL 1: Acessar a nova funcionalidade de carteirinha no portal FHB
    METHOD 1.A: Navegar pelo menu principal do portal
      (SEL. RULE: O familiar cuidador está na página inicial do portal e prefere navegação exploratória por menus)
      OP. 1.A.1: Deslocar o foco visual para o menu superior (Operador cognitivo/perceptivo)
      OP. 1.A.2: Tocar no menu "Doença Falciforme" (Operador físico)
      OP. 1.A.3: Tocar no submenu "Para pacientes" (Operador físico)
      OP. 1.A.4: Examinar a tela em busca da nova funcionalidade destacada (Operador cognitivo)
      OP. 1.A.5: Tocar no link "Carteirinha de identificação" (Operador físico)
      
    METHOD 1.B: Utilizar a barra de busca do portal
      (SEL. RULE: O familiar cuidador tem urgência e prefere ir direto ao alvo digitando o termo)
      OP. 1.B.1: Tocar no ícone de lupa/busca no topo do site (Operador físico)
      OP. 1.B.2: Digitar "Carteirinha Doença Falciforme" (Operador físico)
      OP. 1.B.3: Tocar no botão de buscar (Operador físico)
      OP. 1.B.4: Examinar resultados da busca apresentados (Operador cognitivo)
      OP. 1.B.5: Tocar no link correspondente à emissão da carteirinha (Operador físico)

  GOAL 2: Solicitar a Carteirinha de Identificação
    METHOD 2.A: Autopreenchimento integrado via CPF
      (SEL. RULE: O sistema possui integração nativa e o familiar cuidador tem apenas o CPF do paciente memorizado ou em mãos)
      OP. 2.A.1: Tocar no campo "CPF do Paciente" (Operador físico)
      OP. 2.A.2: Digitar os números do CPF do paciente (Operador físico)
      OP. 2.A.3: Aguardar carregamento (cache) dos dados puxados do sistema de saúde (Operador cognitivo/espera)
      OP. 2.A.4: Ler a tela para conferir o preenchimento automático (nome, tipagem sanguínea, etc.) (Operador cognitivo)
      OP. 2.A.5: Tocar no botão "Confirmar Solicitação e Avançar" (Operador físico)

  GOAL 3: Preencher os dados complementares e fazer upload da foto do documento
    METHOD 3.A: Preenchimento dos dados e upload via formulário integrado
      (SEL. RULE: O familiar cuidador já possui os dados do paciente e a foto do documento disponível no smartphone)
      OP. 3.A.1: Examinar o formulário de dados complementares apresentado pelo sistema (Operador cognitivo)
      OP. 3.A.2: Tocar nos campos correspondentes e preencher os dados solicitados do paciente (Operador físico)
      OP. 3.A.3: Tocar no botão "Adicionar Foto do Documento" (Operador físico)
      OP. 3.A.4: Selecionar a foto da galeria do smartphone ou capturar nova imagem (Operador físico)
      OP. 3.A.5: Verificar visualmente o preview da imagem carregada (Operador cognitivo)

  GOAL 4: Selecionar a opção de emissão do laudo de fenotipagem sanguínea
    METHOD 4.A: Ativar a solicitação do laudo via checkbox dedicado
      (SEL. RULE: O paciente necessita do laudo atualizado para garantir a segurança transfusional)
      OP. 4.A.1: Localizar visualmente a seção "Laudo de Fenotipagem Sanguínea" na tela (Operador cognitivo)
      OP. 4.A.2: Tocar no checkbox "Solicitar Laudo de Fenotipagem Sanguínea" (Operador físico)
      OP. 4.A.3: Ler a informação contextual exibida pelo sistema sobre a finalidade do laudo (Operador cognitivo)

  GOAL 5: Enviar a solicitação e receber o feedback do sistema
    METHOD 5.A: Confirmação e leitura da mensagem de retorno
      (SEL. RULE: O familiar cuidador deseja confirmar que a solicitação foi recebida antes de sair do portal)
      OP. 5.A.1: Tocar no botão "Enviar Solicitação" (Operador físico)
      OP. 5.A.2: Aguardar o processamento da solicitação pelo sistema (Operador cognitivo/espera)
      OP. 5.A.3: Ler a mensagem de confirmação indicando que o sistema buscará o laudo na base e o enviará para o e-mail cadastrado (Operador cognitivo)
  
  GOAL 6: Obter o comprovante da solicitação
    METHOD 6.A: Salvar comprovante via captura de tela (Screenshot)
      (SEL. RULE: O familiar cuidador acessa via smartphone, tem pouco pacote de dados/espaço e tem dificuldade para baixar ou gerenciar arquivos em PDF)
      OP. 6.A.1: Ler a mensagem de sucesso exibida de forma ampla na tela (Operador cognitivo)
      OP. 6.A.2: Conferir visualmente a data da solicitação e o número de protocolo gerado (Operador cognitivo)
      OP. 6.A.3: Pressionar simultaneamente os botões físicos do smartphone para tirar "print" (Operador físico)
      OP. 6.A.4: Verificar o alerta rápido do sistema operacional indicando que a imagem foi salva na galeria (Operador cognitivo)
 
    METHOD 6.B: Baixar o comprovante oficial em PDF
      (SEL. RULE: O familiar cuidador prefere ter o arquivo oficial salvo para impressão futura e possui familiaridade com arquivos)
      OP. 6.B.1: Ler a mensagem de sucesso na tela (Operador cognitivo)
      OP. 6.B.2: Tocar no botão "Baixar Protocolo em PDF" (Operador físico)

```

## Referências Bibliográficas

> <a id="ref1"></a> [1] BARBOSA, Simone Diniz Junqueira et al. *Interação Humano-Computador e Experiência do Usuário*. 1. ed. Rio de Janeiro: Autopublicação, 2021.

## Histórico de Versões

| Versão | Descrição | Data | Autor(es) | Data de revisão | Revisor(es) |
| ------ | ------ | ------ | ------ | ------ | ------ |
| 1.0 | Criação do GOMS da Persona 5 | 02/05/2026 | [Julia Gabriella](https://github.com/juliagabriellafs) | 03/05/2026 | [Gabriel Diniz](https://github.com/GabrielDiniz12) |
| 2.0 | Revisão do GOMS da Persona 5 | 21/06/2026 | [Julia Gabriella](https://github.com/juliagabriellafs) | 21/06/2026 | [Pedro Américo](https://github.com/dev-americo)|