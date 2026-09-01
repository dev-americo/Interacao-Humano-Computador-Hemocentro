## Introdução

O [GOMS](#ref1) é um método de análise de tarefas em Interação Humano-Computador focado em descrever o comportamento de **usuários competentes**, ou seja, aqueles que já dominam as rotinas do sistema e não cometem erros. 

A interação é estruturada em 4 componentes básicos:

- **Objetivos (*Goals*):** O que o usuário deseja realizar no sistema.
- **Operadores (*Operators*):** As ações físicas (como clicar ou teclar) e cognitivas (mentais) necessárias.
- **Métodos (*Methods*):** A sequência exata de passos e operadores para se atingir um objetivo.
- **Regras de Seleção (*Selection Rules*):** A decisão do usuário sobre qual método escolher quando o sistema oferece mais de um caminho para o mesmo objetivo.

## Analise GOMS - Solicitação Urgente de Bolsa de Sangue Fenotipado

Abaixo segue a análise GOMS

```
GOAL 0: Solicitar Bolsa de Sangue Fenotipado em caráter de urgência
     GOAL 1: Acessar o Módulo Digital de Solicitação de Hemocomponentes         
        METHOD 1.A: Acesso através do menu institucional             
        (SEL. RULE: O usuário já conhece a arquitetura de informação do site ou prefere navegar pelos menus)
            OP. 1.A.1: Deslocar o mouse para o menu principal "Hemorrede DF"
            OP. 1.A.2: Clicar na opção "Unidades conveniadas"
            OP. 1.A.3: Ler a tela para localizar a seção "Solicitação e transfusão"
            OP. 1.A.4: Clicar para abrir o Módulo Digital de Hemocomponentes
        METHOD 1.B: Acesso direto via barra de busca             
        (SEL. RULE: O usuário tem pressa extrema, não quer procurar em seções e prefere usar atalhos de texto)
            OP. 1.B.1: Deslocar o mouse para a barra de busca do portal
            OP. 1.B.2: Digitar os termos "Solicitar sangue fenotipado"             
            OP. 1.B.3: Pressionar a tecla 'Enter' (ou clicar na lupa) para buscar
            OP. 1.B.4: Ler a tela para avaliar os resultados
            OP. 1.B.5: Clicar no link do Módulo Digital de Hemocomponentes
    GOAL 2: Preencher o laudo e as especificações da bolsa
         METHOD 2.A: Digitação e seleção de opções integradas no formulário digital             
            OP. 2.A.1: Ler a tela para identificar os campos clínicos exigidos
            OP. 2.A.2: Deslocar o mouse e clicar no campo de identificação do paciente             
            OP. 2.A.3: Digitar os dados do paciente e o laudo de compatibilidade imunológica
            OP. 2.A.4: Deslocar o mouse para o controle de opções (checkbox/radio button) de prioridade             
            OP. 2.A.5: Clicar para selecionar o caráter de "Urgência"
            OP. 2.A.6: Deslocar o mouse para a lista de especificações da bolsa             
            OP. 2.A.7: Clicar para selecionar "Doador Fenotipado"
    GOAL 3: Efetivar a solicitação urgencial
         METHOD 3.A: Envio direto através do próprio portal             
            OP. 3.A.1: Deslocar o mouse para o botão de envio             
            OP. 3.A.2: Clicar no botão para efetivar e registrar a solicitação
            OP. 3.A.3: Ler a tela para perceber a resposta do sistema (feedback/status)
            OP. 3.A.4: Interpretar a mensagem de sucesso indicando que o Hemocentro recebeu o pedido
```

## Referências Bibliográficas

> <a id="ref1"></a> [1] BARBOSA, Simone Diniz Junqueira et al. *Interação Humano-Computador e Experiência do Usuário*. 1. ed. Rio de Janeiro: Autopublicação, 2021.

## Histórico de Versões

| Versão | Descrição | Data | Autor(es) | Data de revisão | Revisor(es) |
| :---: | :--- | :---: | :---: | :---: | :---: |
| 1.0 | Criação do documento da tarefa CMN-GOMS | 02/05/2026 | [Pedro Lucas](https://github.com/pwdrinho)| 03/05/2026 | [Breno Teixeira](https://github.com/BrenoLTeixeira) |