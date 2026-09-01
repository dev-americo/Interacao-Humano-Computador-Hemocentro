## Introdução

O [GOMS](#ref1) é um método de análise de tarefas em Interação Humano-Computador focado em descrever o comportamento de **usuários competentes**, ou seja, aqueles que já dominam as rotinas do sistema e não cometem erros. 

A interação é estruturada em 4 componentes básicos:

- **Objetivos (*Goals*):** O que o usuário deseja realizar no sistema.
- **Operadores (*Operators*):** As ações físicas (como clicar ou teclar) e cognitivas (mentais) necessárias.
- **Métodos (*Methods*):** A sequência exata de passos e operadores para se atingir um objetivo.
- **Regras de Seleção (*Selection Rules*):** A decisão do usuário sobre qual método escolher quando o sistema oferece mais de um caminho para o mesmo objetivo.

## Analise GOMS - Doação em Grupo

Abaixo segue a análise GOMS

```
GOAL 0: organizar doação em grupo com transporte
    GOAL 1: criar a campanha solidária no sistema
        METHOD 1: preencher formulário simplificado de escopo
            OP. 1.1: preencher dados do grupo/empresa (Nome da campanha, telefone)
            OP. 1.2: inserir quantidade estimada de doadores (entre 10 e 19 pessoas)
            OP. 1.3: acionar botão "Avançar"
            
    GOAL 2: agendar transporte logístico (van HemoTour)
        METHOD 2: reservar horário no calendário interativo
            OP. 2.1: visualizar os dias com disponibilidade de frota no calendário
            OP. 2.2: clicar sobre a data e o horário desejados
            OP. 2.3: digitar o endereço de partida e retorno da van
            OP. 2.4: acionar o botão "Confirmar Agendamento"
            OP. 2.5: verificar o feedback visual de sucesso na tela (ícone verde de confirmação)
            
    GOAL 3: convidar doadores para realizar o Verificador de Aptidão
        METHOD 3.A: compartilhar via integração direta nativa
            (SEL. RULE: o usuário está utilizando um smartphone e prefere a agilidade do compartilhamento nativo para grupos de trabalho)
            OP. 3.A.1: deslocar o foco para o botão "Compartilhar no WhatsApp"
            OP. 3.A.2: acionar o botão (redirecionamento automático)
            
        METHOD 3.B: compartilhar via cópia manual de link
            (SEL. RULE: o usuário está utilizando o sistema via desktop ou prefere redigir um e-mail/mensagem personalizada antes de colar o link)
            OP. 3.B.1: deslocar o cursor para o botão "Copiar Link"
            OP. 3.B.2: clicar com o botão esquerdo do mouse
            OP. 3.B.3: colar o link na plataforma de comunicação desejada

```
## Referências Bibliográficas

> <a id="ref1"></a> [1] BARBOSA, Simone Diniz Junqueira et al. *Interação Humano-Computador e Experiência do Usuário*. 1. ed. Rio de Janeiro: Autopublicação, 2021.

## Histórico de Versões

| Versão | Descrição | Data | Autor(es) | Data de revisão | Revisor(es) |
| :---: | :--- | :---: | :---: | :---: | :---: |
| 1.0 | Analise GOMS | 03/05/2026 | [Pedro Américo](https://github.com/dev-americo)| 03/05/2026 | [Pedro Ian](https://github.com/pedroiaan) |