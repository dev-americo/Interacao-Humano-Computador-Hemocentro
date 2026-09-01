## Introdução

Esta seção demonstra o site escolhido para a realização do trabalho, possuindo os motivos e os critarios que justificaram a escolha do site.

## Motivação para a Escolha

A escolha do portal da Fundação Hemocentro de Brasília (e sua integração com o sistema de agendamento Agenda DF) foi motivada pela elevada relevância social do serviço oferecido (cadastro e doação de sangue/medula óssea) e pela presença de severos atritos de interação que podem levar ao abandono da tarefa. Sites [governamentais devem¹](#ref1):

- Servir a todos os cidadãos de forma igualitária
- Remover barreiras de acesso nas comunicações e informações
- Respeitar os diferentes níveis de letramento digital da população.

Entretanto, uma [análise preliminar²](#ref1) demonstrou que o sistema atual possui falhas de comunicação com o usuário. O fluxo de interação exige que o cidadão possua um modelo mental da estrutura burocrática do Estado, forçando-o a sair do site do Hemocentro e tentar localizá-lo novamente em uma grade genérica de múltiplos órgãos no portal "Agenda DF". Somado a isso, a etapa final do agendamento exige uma autenticação abrupta por meio do portal "gov.br" ou "Participa DF", criando uma quebra na operação que não oferece ajuda preventiva. Avaliar esse sistema é uma oportunidade valiosa de aplicar a disciplina de Interação Humano-Computador para evitar que a má qualidade de uso da tecnologia atue como um obstáculo a um serviço essencial de saúde pública, melhorando a forma como a tecnologia é inserida na vida do cidadão.

## Critérios de Escolha

Para fundamentar a escolha deste sistema de forma técnica e acadêmica para o trabalho, estabelecemos os seguintes critérios metodológicos:

* **Criticidade do Domínio e Consequência da Falha:** O processo de agendamento de doações possui uma tolerância muito baixa para falhas na interação. Caso o sistema não guie o usuário de forma clara ou não previna erros, a consequência da falha não é apenas um incômodo, mas a perda real de um doador para o Hemocentro. Sistemas com essas características são objetos de estudo riquíssimos para a disciplina de IHC, cujos problemas identificados devem ser inspecionados e classificados de acordo com sua gravidade e impacto nocivo.

* **Violações Críticas de Heurísticas de Usabilidade:** O sistema apresenta problemas graves de padronização e visibilidade do status do sistema. Como detectado na inspeção preliminar, o sistema oculta a principal ação de avanço do agendamento em um pequeno texto clicável de "linha miúda", fugindo do padrão mental do usuário que espera um botão de "Próximo". Essa falha gera um altíssimo risco de o usuário fechar a janela acreditando que a vaga já foi garantida antes mesmo de efetivar a autenticação exigida, o que fere gravemente a heurística de manter os usuários informados sobre o que está acontecendo no sistema.

* **Inadequação ao Perfil do Usuário (Letramento Digital):** O perfil estabelecido para a avaliação abrange usuários de 18 a 30 anos com baixo letramento digital. O sistema falha criticamente em apoiar esse perfil, refletindo uma abordagem de desenvolvimento "centrada no sistema", onde o software expõe a visão interna e os processos do governo, em vez de seguir uma abordagem "centrada no uso", que deveria focar em facilitar o alcance do objetivo do usuário de forma fluida e livre de sobrecarga cognitiva.

## Referências Bibliográficas

<a id="ref1"></a>
> [1] BRASIL. Decreto nº 5.296, de 2 de dezembro de 2004. Regulamenta as Leis nº 10.048, de 8 de novembro de 2000, e nº 10.098, de 19 de dezembro de 2000. Brasília, DF: Presidência da República, 2004. Disponível em: <https://www.planalto.gov.br/ccivil_03/_ato2004-2006/2004/decreto/d5296.htm>. Acesso em: 9 abr. 2026.

> [2] SÁ, Pedro Henrique Américo de. Tópico: Planejamento de avaliação e Executar uma avaliação de um site [Projeto Parte Individual Método e Avaliação]. . Trabalho acadêmico (Disciplina Interação Humano Computador) – Faculdade UnB Gama, Universidade de Brasília, Brasília, DF. Disponível em: <a href="../../assets/pdfs/avaliacao_hemocentro.pdf" target="_blank">  Avaliação do Hemocentro</a>. Acesso em: 10 abr. 2026.

## Bibliografia
> BARBOSA, Simone Diniz Junqueira et al. Interação Humano-Computador e Experiência do Usuário. 1. ed. Rio de Janeiro: Simone Diniz Junqueira Barbosa, 2021. E-book.

---

## Histórico de Versões

| Versão | Descrição | Data | Autor(es) | Data de revisão | Revisor(es) |
| :---: | :--- | :---: | :---: | :---: | :---: |
| 1.0 | Criação do documento, definição da motivação e critérios de escolha. | 10/04/2026 | [Gabriel Diniz](https://github.com/GabrielDiniz12)| 10/04/2026 | [Julia Gabriella](https://github.com/juliagabriellafs)|
| 1.1 | Revisão após inspeção da entrega 1 | 11/04/2026 | [Gabriel Diniz](https://github.com/GabrielDiniz12)| 11/04/2026 | [Julia Gabriella](https://github.com/juliagabriellafs)|