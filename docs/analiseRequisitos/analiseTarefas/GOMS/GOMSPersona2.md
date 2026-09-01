## Introdução

O [GOMS](#ref1) é um método de análise de tarefas em Interação Humano-Computador focado em descrever o comportamento de **usuários competentes**, ou seja, aqueles que já dominam as rotinas do sistema e não cometem erros. 

A interação é estruturada em 4 componentes básicos:

- **Objetivos (*Goals*):** O que o usuário deseja realizar no sistema.
- **Operadores (*Operators*):** As ações físicas (como clicar ou teclar) e cognitivas (mentais) necessárias.
- **Métodos (*Methods*):** A sequência exata de passos e operadores para se atingir um objetivo.
- **Regras de Seleção (*Selection Rules*):** A decisão do usuário sobre qual método escolher quando o sistema oferece mais de um caminho para o mesmo objetivo.

## Analise GOMS - Solicitar Dispensação Domiciliar de Medicação

Abaixo segue a análise GOMS

```
GOAL 0: Solicitar dispensação domiciliar de medicação
  GOAL 1: Acessar o sistema
    METHOD 1.A: Navegar através do portal do Hemocentro
      [Mover o mouse para a seção "Portal do Paciente"]
      [Clicar no link de acesso]
      [Digitar as credenciais de login]
      [Pressionar a tecla "Enter"]

  GOAL 2: Acessar a funcionalidade Entrega Domiciliar
    METHOD 2.A: Localizar o serviço no painel principal
      [Ler a tela carregada identificando o menu de serviços]
      [Mover o mouse para o botão "Solicitar Entrega Domiciliar"]
      [Clicar no botão]

  GOAL 3: Fazer o upload do relatório médico
    METHOD 3.A: Selecionar arquivo salvo no computador
    (SEL. RULE: Júlia já transferiu a foto do relatório do celular para o notebook)
      [Mover o mouse para o campo "Anexar Relatório (.pdf, .jpg, .png)"]
      [Clicar no botão de upload]
      [Localizar o arquivo na janela do explorador de arquivos]
      [Clicar no arquivo desejado]
      [Clicar no botão "Abrir"]
      [Ler a mensagem de confirmação de upload concluído]

  GOAL 4: Confirmar detalhes e finalizar solicitação
    GOAL 4.1: Validar endereço de entrega
      METHOD 4.1.A: Confirmar dados pré-cadastrados
        [Ler o endereço residencial exibido na tela]
        [Mover o mouse para a caixa de seleção "Confirmar endereço cadastrado"]
        [Clicar na caixa de seleção]

    GOAL 4.2: Enviar a solicitação final
      METHOD 4.2.A: Finalizar utilizando o mouse
      (SEL. RULE: A usuária já está com a mão no mouse após validar o endereço)
        [Mover o mouse para o botão "Confirmar Solicitação de Entrega"]
        [Clicar no botão]
        [Ler a tela com a mensagem de sucesso e o número do protocolo]

      METHOD 4.2.B: Finalizar utilizando atalho de teclado
      (SEL. RULE: Júlia deseja agilidade e já terminou de preencher os dados)
        [Pressionar a tecla "Enter" no teclado]
        [Ler a tela com a mensagem de sucesso e o número do protocolo]
```

## Referências Bibliográficas

> <a id="ref1"></a> [1] BARBOSA, Simone Diniz Junqueira et al. *Interação Humano-Computador e Experiência do Usuário*. 1. ed. Rio de Janeiro: Autopublicação, 2021.

## Histórico de Versões

| Versão | Descrição | Data | Autor(es) | Data de revisão | Revisor(es) |
| :---: | :--- | :---: | :---: | :---: | :---: |
| 1.0 | Criação do documento da tarefa CMN-GOMS (Persona 2) | 02/05/2026 | [Breno Teixeira](https://github.com/brenolteixeira)| 03/05/2026 | [Pedro Américo](https://github.com/dev-americo) |