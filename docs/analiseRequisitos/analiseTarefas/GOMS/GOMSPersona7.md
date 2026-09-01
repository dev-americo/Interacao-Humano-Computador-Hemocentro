## Introdução

O [GOMS](#ref1) é um método de análise de tarefas em Interação Humano-Computador focado em descrever o comportamento de **usuários competentes**, ou seja, aqueles que já dominam as rotinas do sistema e não cometem erros. 

A interação é estruturada em 4 componentes básicos:

- **Objetivos (*Goals*):** O que o usuário deseja realizar no sistema.
- **Operadores (*Operators*):** As ações físicas (como clicar ou teclar) e cognitivas (mentais) necessárias.
- **Métodos (*Methods*):** A sequência exata de passos e operadores para se atingir um objetivo.
- **Regras de Seleção (*Selection Rules*):** A decisão do usuário sobre qual método escolher quando o sistema oferece mais de um caminho para o mesmo objetivo.

## Analise GOMS - Triagem Digital

```text
GOAL 0: Realizar triagem para Sangria Terapêutica e gerenciar o redirecionamento
    GOAL 1: Acessar o sistema de triagem
        METHOD 1.A: Navegação pelos menus do portal via Smartphone
            (SEL. RULE: O usuário está na página inicial do site da FHB pelo celular)
            Ler os menus disponíveis na tela
            Mover o dedo para o menu "Quero doar"
            Tocar no menu "Quero doar"
            Ler as opções do submenu
            Mover o dedo para a subpágina "Antes de doar"
            Tocar na subpágina "Antes de doar"
            Rolar a tela procurando por "Sangria Terapêutica"
            Tocar na opção "Sangria Terapêutica"
            Ler a descrição inicial da página
            Mover o dedo para o botão "Iniciar Triagem para Sangria"
            Tocar no botão "Iniciar Triagem para Sangria"
            Aguardar o carregamento do questionário
            
    GOAL 2: Responder ao questionário de validação
        METHOD 2.A: Confirmar origem externa da receita
            Ler a Pergunta: "O pedido foi feito por um médico externo/particular?"
            Avaliar as opções de resposta apresentadas ("Sim" ou "Não")
            Decidir que a resposta correta para a sua situação é "Sim"
            Mover o dedo para a opção "Sim"
            Tocar na opção "Sim"
            Aguardar o processamento e o redirecionamento automático do sistema
            
    GOAL 3: Receber o redirecionamento e salvar o endereço de encaminhamento
        METHOD 3.A: Salvar endereço via integração com WhatsApp
            (SEL. RULE: O usuário tem baixo letramento para gerenciar arquivos no celular, possui o WhatsApp como principal ferramenta de comunicação e prefere praticidade)
            Ler o alerta "Atendimento Incompatível" em destaque
            Ler as opções de salvamento disponíveis (PDF ou WhatsApp)
            Decidir utilizar o botão do WhatsApp
            Mover o dedo para o botão "Enviar para o WhatsApp"
            Tocar no botão "Enviar para o WhatsApp"
            Aguardar a abertura automática do aplicativo WhatsApp
            Tocar no botão de "Enviar" mensagem no aplicativo
            
        METHOD 3.B: Salvar endereço via download de PDF
            (SEL. RULE: O usuário possui familiaridade com o sistema de arquivos do smartphone e prefere baixar o documento oficial para imprimir posteriormente)
            Ler o alerta "Atendimento Incompatível" em destaque
            Ler as opções de salvamento disponíveis (PDF ou WhatsApp)
            Decidir utilizar o botão de baixar PDF
            Mover o dedo para o botão "Baixar Guia de Encaminhamento SES-DF"
            Tocar no botão "Baixar Guia de Encaminhamento SES-DF"
            Aguardar a conclusão do download do arquivo
            
    GOAL 4: Encerrar a tarefa
        METHOD 4.A: Fechar a página do navegador
            Mover o dedo para o gerenciador de abas/botão de fechar do navegador
            Tocar no botão para fechar a página
```

## Referências Bibliográficas

> <a id="ref1"></a> [1] BARBOSA, Simone Diniz Junqueira et al. *Interação Humano-Computador e Experiência do Usuário*. 1. ed. Rio de Janeiro: Autopublicação, 2021.

## Histórico de Versões

| Versão | Descrição | Autor(es) | Data | Revisor(es) | Data de revisão |
| :---: | :--- | :---: | :---: | :---: | :---: |
| 1.0 | Criação do CMN-GOMS (To-Be) da persona Antiusuário | [Pedro Ian](https://github.com/pedroiaan) | 01/05/2026 | [Lucas Oliveira](https://github.com/dev-LucasDpaula) | 03/05/2026 |