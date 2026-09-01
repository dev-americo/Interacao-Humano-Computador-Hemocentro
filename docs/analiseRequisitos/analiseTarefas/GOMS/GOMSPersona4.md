## Introdução

O [GOMS](#ref1) é um método de análise de tarefas em Interação Humano-Computador focado em descrever o comportamento de **usuários competentes**, ou seja, aqueles que já dominam as rotinas do sistema e não cometem erros. 

A interação é estruturada em 4 componentes básicos:

- **Objetivos (*Goals*):** O que o usuário deseja realizar no sistema.
- **Operadores (*Operators*):** As ações físicas (como clicar ou teclar) e cognitivas (mentais) necessárias.
- **Métodos (*Methods*):** A sequência exata de passos e operadores para se atingir um objetivo.
- **Regras de Seleção (*Selection Rules*):** A decisão do usuário sobre qual método escolher quando o sistema oferece mais de um caminho para o mesmo objetivo.

## Analise GOMS - Notificar Reação Transfusional (FIRT Digital)

Abaixo segue a análise GOMS

```
GOAL 0: Notificar Reação Transfusional (FIRT Digital) e bloquear lote  
  GOAL 1: Acessar o sistema
    METHOD 1.A: Navegar através dos menus do portal  
      OP. 1.A.1: Mover o mouse para o menu principal "Hemorrede DF"
      OP. 1.A.2: Clicar no link "Unidades conveniadas"
      OP. 1.A.3: Digitar as credenciais de acesso
      OP. 1.A.4: Pressionar a tecla "Enter"

  GOAL 2: Acessar a nova funcionalidade FIRT Digital
    METHOD 2.A: Acessar através do painel logado
      OP. 2.A.1: Ler a tela carregada identificando a seção logada
      OP. 2.A.2: Mover o mouse para o botão "Notificação Compulsória de Reação Transfusional"
      OP. 2.A.3: Clicar no botão
        
  GOAL 3: Preencher os dados da reação transfusional  
    GOAL 3.1: Informar o número de identificação da bolsa suspeita  
      METHOD 3.1.A: Digitar número manualmente  
      (SEL. RULE: A enfermeira não possui leitor de código de barras no posto e a bolsa está em suas mãos)  
        OP. 3.1.A.1: Mover o mouse para o campo "Número de identificação da bolsa"
        OP. 3.1.A.2: Clicar no campo  
        OP. 3.1.A.3: Ler o número impresso na bolsa física
        OP. 3.1.A.4: Digitar o número da bolsa no teclado
          
    GOAL 3.2: Informar os dados clínicos do paciente  
      METHOD 3.2.A: Digitar os dados utilizando o teclado  
        OP. 3.2.A.1: Mover o mouse para o campo "Dados clínicos" 
        OP. 3.2.A.2: Clicar no campo  
        OP. 3.2.A.3: Digitar o nome e os sinais vitais do paciente  
          
    GOAL 3.3: Selecionar os sintomas apresentados  
      METHOD 3.3.A: Marcar as opções de sintomas na tela  
        OP. 3.3.A.1: Ler as opções de sintomas disponíveis
        OP. 3.3.A.2: Mover o mouse para a caixa de seleção (checkbox) "Calafrios" 
        OP. 3.3.A.3: Clicar na caixa de seleção  
        OP. 3.3.A.4: Mover o mouse para a caixa de seleção (checkbox) "Febre"  
        OP. 3.3.A.5: Clicar na caixa de seleção  
          
  GOAL 4: Enviar a notificação compulsória  
    METHOD 4.A: Enviar o formulário utilizando o mouse  
    (SEL. RULE: A mão da enfermeira já está sobre o mouse após marcar os sintomas)  
      OP. 4.A.1: Mover o mouse para o botão "Enviar Notificação Compulsória / Bloquear Lote"
      OP. 4.A.2: Clicar no botão
      OP. 4.A.3: Ler a tela com o alerta visual de confirmação do bloqueio preventivo
        
    METHOD 4.B: Enviar o formulário utilizando atalho de teclado  
    (SEL. RULE: A enfermeira prefere a agilidade do teclado pela urgência da situação clínica)  
      OP. 4.B.1: Pressionar a tecla "Enter" no teclado
      OP. 4.B.2: Ler a tela com o alerta visual de confirmação do bloqueio preventivo
```

## Referências Bibliográficas

> <a id="ref1"></a> [1] BARBOSA, Simone Diniz Junqueira et al. *Interação Humano-Computador e Experiência do Usuário*. 1. ed. Rio de Janeiro: Autopublicação, 2021.

## Histórico de Versões

| Versão | Descrição | Data | Autor(es) | Data de revisão | Revisor(es) |
| :---: | :--- | :---: | :---: | :---: | :---: |
| 1.0 | Criação do documento da tarefa CMN-GOMS | 01/05/2026 | [Gabriel Diniz](https://github.com/GabrielDiniz12)| 02/05/2026 | [Pedro Lucas](https://github.com/pwdrinho) |
| 1.1 | Adiciona Introdução corrige padrão CMN-GOMS com base no livro | 02/05/2026 | [Pedro Lucas](https://github.com/pwdrinho)| 03/05/2026 | [Gabriel Diniz](https://github.com/GabrielDiniz12) |