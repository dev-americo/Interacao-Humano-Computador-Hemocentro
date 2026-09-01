## Introdução

O [GOMS](#ref1) é um método de análise de tarefas em Interação Humano-Computador focado em descrever o comportamento de **usuários competentes**, ou seja, aqueles que já dominam as rotinas do sistema e não cometem erros. 

A interação é estruturada em 4 componentes básicos:

- **Objetivos (*Goals*):** O que o usuário deseja realizar no sistema.
- **Operadores (*Operators*):** As ações físicas (como clicar ou teclar) e cognitivas (mentais) necessárias.
- **Métodos (*Methods*):** A sequência exata de passos e operadores para se atingir um objetivo.
- **Regras de Seleção (*Selection Rules*):** A decisão do usuário sobre qual método escolher quando o sistema oferece mais de um caminho para o mesmo objetivo.

## Analise GOMS - Agendar HemoTour e Enviao de Autorizações

```
GOAL 0: Agendar HemoTour e enviar autorizações em lote
  
  GOAL 1: Acessar o formulário de agendamento da Visita Técnica
    METHOD 1.A: Navegar pelos menus principais com o mouse
      OP. 1.A.1: Mover o mouse para o menu "Educação" (Operador físico)
      OP. 1.A.2: Aguardar a expansão do submenu (Operador cognitivo/espera)
      OP. 1.A.3: Mover o mouse para a opção "Visita técnica" (Operador físico)
      OP. 1.A.4: Clicar com o botão esquerdo (Operador físico)
      OP. 1.A.5: Ler a tela para localizar o botão de ação (Operador cognitivo/perceptivo)
      OP. 1.A.6: Mover o mouse para o botão "Agendar Visita" (Operador físico)
      OP. 1.A.7: Clicar com o botão esquerdo (Operador físico)

  GOAL 2: Selecionar data e horário no calendário interativo
    METHOD 2.A: Escolher data visualmente no componente de calendário
      OP. 2.A.1: Ler a tela para verificar os dias com vagas (em verde) (Operador cognitivo/perceptivo)
      OP. 2.A.2: Mover o mouse para o dia desejado (ex: próxima sexta-feira) (Operador físico)
      OP. 2.A.3: Clicar com o botão esquerdo na data (Operador físico)
      OP. 2.A.4: Ler a tela para ver os horários disponíveis (Operador cognitivo)
      OP. 2.A.5: Mover o mouse para o horário das "09:00" (Operador físico)
      OP. 2.A.6: Clicar com o botão esquerdo (Operador físico)

  GOAL 3: Anexar as 15 autorizações dos pais em PDF
    METHOD 3.A: Anexar via botão Explorador de Arquivos do sistema
      (SEL. RULE: Se a janela do navegador estiver em tela cheia e a pasta não estiver visível)
      OP. 3.A.1: Mover o mouse para o botão "Buscar Arquivos" (Operador físico)
      OP. 3.A.2: Clicar com o botão esquerdo (Operador físico)
      OP. 3.A.3: Ler a tela da janela pop-up do Windows/Mac (Operador cognitivo/perceptivo)
      OP. 3.A.4: Navegar até a pasta "Autorizações HemoTour" (Operador físico)
      OP. 3.A.5: Pressionar atalho Ctrl+A (ou arrastar o mouse) para selecionar os 15 PDFs (Operador físico)
      OP. 3.A.6: Clicar no botão "Abrir" do sistema operacional (Operador físico)

    METHOD 3.B: Anexar via Drag and Drop / Arrastar e Soltar
      (SEL. RULE: Se o usuário já estiver com a pasta de arquivos aberta e visível ao lado do navegador)
      OP. 3.B.1: Mover o mouse para a janela da pasta no computador (Operador físico)
      OP. 3.B.2: Pressionar atalho Ctrl+A para selecionar os 15 PDFs (Operador físico)
      OP. 3.B.3: Pressionar e segurar o clique esquerdo sobre os arquivos (Operador físico)
      OP. 3.B.4: Mover o mouse (arrastar) para a área tracejada "Solte seus PDFs aqui" no navegador (Operador físico)
      OP. 3.B.5: Soltar o clique esquerdo (Operador físico)

  GOAL 4: Confirmar a submissão e finalizar o agendamento
    METHOD 4.A: Submeter o formulário completo
      OP. 4.A.1: Ler a tela para checar a barra de progresso indicando "15 arquivos carregados" (Operador cognitivo/perceptivo)
      OP. 4.A.2: Mover o mouse para o botão final "Confirmar Agendamento" (Operador físico)
      OP. 4.A.3: Clicar com o botão esquerdo (Operador físico)
      OP. 4.A.4: Aguardar o processamento do sistema (Operador cognitivo/espera)
      OP. 4.A.5: Ler a tela para capturar o "Número de Protocolo" gerado com sucesso (Operador cognitivo)
```

## Referências Bibliográficas

> <a id="ref1"></a> [1] BARBOSA, Simone Diniz Junqueira et al. *Interação Humano-Computador e Experiência do Usuário*. 1. ed. Rio de Janeiro: Autopublicação, 2021.

## Histórico de Versões

| Versão | Descrição | Data | Autor(es) | Data de revisão | Revisor(es) |
| :---: | :--- | :---: | :---: | :---: | :---: |
| 1.0 | Criação do CMN-GOMS (To-Be) da persona Antiusuário | 01/05/2026 | [Pedro Ian](https://github.com/pedroiaan) | 03/05/2026 | [Lucas Oliveira](https://github.com/dev-LucasDpaula) |
