# Relato dos Resultados da Avaliação da Análise de Tarefas

### Tabela de Contribuição

| Integrante | Tópicos de Contribuição |
| :--- | :--- |
| [Breno Teixeira](https://github.com/BrenoLTeixeira) | Funcionalidade 2<br>3. Seleção dos Participantes <br>Introdução |
| [Gabriel Diniz](https://github.com/GabrielDiniz12) | Funcionalidade 4<br>3. Seleção dos Participantes<br>Lista de problemas encontrados<br>Feedback dos Usuários |
| [Júlia Gabriella](https://github.com/juliagabriellafs) | Funcionalidade 5<br>3. Seleção dos Participantes Realidade<br>1. Objetivo e Escopo da Avaliação |
| [Lucas Oliveira](https://github.com/dev-LucasDpaula) | Funcionalidade 6<br>3. Seleção dos Participantes<br>7. Planejamento de Reprojeto|
| [Pedro Américo](https://github.com/dev-americo) | Funcionalidade 1<br>3. Seleção dos Participantes Realidade<br>6. Análise e Interpretação dos Resultados |
| [Pedro Ian](https://github.com/pedroiaan) | Funcionalidade 7<br>3. Seleção dos Participantes<br>7. Planejamento de Reprojeto |
| [Pedro Lucas](https://github.com/Pwdrinho) | Funcionalidade 3<br>3. Seleção dos Participantes<br>2. Método de Avaliação<br>Lista de problemas encontrados<br>Feedback dos Usuários |
---

## Introdução

Este documento apresenta o relato dos resultados da avaliação dos artefatos de Análise de Tarefas produzidos no contexto do reprojeto do portal da **Fundação Hemocentro de Brasília (FHB)**. Sua função é registrar, de forma estruturada e rastreável, o que foi planejado para a avaliação, o que foi efetivamente coletado durante a entrevista com o participante e quais encaminhamentos foram definidos a partir dos dados obtidos.

Conforme [Barbosa e Silva (2021)](#ref1), o relato dos resultados de uma avaliação deve contemplar: os objetivos e o escopo da avaliação; o método empregado; o perfil dos participantes; os problemas e as dificuldades encontradas; as sugestões de melhoria; o feedback dos usuários; a análise e interpretação dos dados; um sumário dos principais resultados; e o planejamento de reprojeto. Este documento segue essa estrutura, adaptada à natureza dos artefatos de Análise de Tarefas — diagramas **HTA (Hierarchical Task Analysis)** e modelos **GOMS (Goals, Operators, Methods and Selection Rules)**.

---

## 1. Objetivo e Escopo da Avaliação

O objetivo geral desta avaliação foi **verificar e validar os artefatos de Análise de Tarefas** produzidos para a funcionalidade proposta no portal da FHB, examinando se os diagramas HTA e os modelos GOMS são tecnicamente corretos, coerentes com a realidade dos usuários do Hemocentro e adequados para fundamentar as próximas etapas do processo de design.

Especificamente, buscou-se:

- Confirmar se a decomposição hierárquica de tarefas do diagrama HTA — incluindo notação, planos de sequência, condições de parada e representação em tabela — está correta e sem inconsistências internas;
- Verificar se os objetivos, operadores e métodos definidos no modelo GOMS correspondem às estratégias reais que um usuário adotaria ao interagir com o portal;
- Identificar subtarefas modeladas de forma equivocada, etapas ausentes ou fluxos alternativos não contemplados, que possam comprometer a fidelidade dos artefatos como base para o design;
- Coletar insumos para orientar a revisão e correção dos artefatos antes do avanço para etapas de maior fidelidade do processo de design.

O escopo desta avaliação está **restrito aos artefatos de Análise de Tarefas** como documentos de modelagem de interação. Questões relativas à implementação do sistema, avaliação de protótipos ou testes de usabilidade não fazem parte do escopo deste documento.

---

## 2. Método de Avaliação

O método utilizado foi uma **entrevista semiestruturada combinada com observação pelo protocolo Think Aloud**. O entrevistador apresentou os artefatos (diagrama HTA e/ou modelo GOMS) de forma progressiva ao participante, conduzindo o roteiro de perguntas definido no Planejamento da Avaliação e incentivando o participante a verbalizar seus pensamentos, dúvidas e discordâncias à medida que analisava cada etapa da tarefa modelada.

Toda sessão foi realizada **obrigatoriamente de forma presencial**, contando sempre com **no mínimo 2 (dois) integrantes do subgrupo**: um responsável por conduzir a entrevista, apresentar os artefatos e anotar as respostas; e outro responsável por **segurar manualmente o celular**, gravando simultaneamente os **artefatos exibidos em tela e o áudio da conversa**.

<font size="3"><p class="table-source"><b>Tabela 1</b> - Funcionalidade: Agendamento em Grupo</p></font>

| Campo                             |Informação                                                                                                                  |
|:----------------------------------|:---------------------------------------------------------------------------------------------------------------------------|
| **Funcionalidade**                | Agendamento de Doação em Grupo                                                                                             |
| **Artefatos avaliados**           | ( ) Diagrama HTA   ( ) Modelo GOMS   ( X ) Ambos                                                                           |
| **Link Perfil de Usuário Alvo**   | [Perfil de Usuário 1](../../../../analiseRequisitos/perfilUsuario/perfilUsuario1)                                            |
| **Link para o diagrama HTA**      | [Analise HTA](../../../../analiseRequisitos/analiseTarefas/HTA/HTAPersona1)                                                |
| **Link para o modelo GOMS**       | [Analise GOMS](../../../../analiseRequisitos/analiseTarefas/HTA/GOMSPersona1)                                              |

<font size="3"><p class="table-source">Fonte: [Pedro Américo](https://github.com/dev-americo).</p></font>

<font size="3"><p class="table-source"><b>Tabela 2</b> - Funcionalidade: Solicitar dispensação domiciliar de medicação</p></font>

| Campo                             |Informação                                                                                                                  |
|:----------------------------------|:---------------------------------------------------------------------------------------------------------------------------|
| **Funcionalidade**                | Solicitar dispensação domiciliar de medicação                                                                                             |
| **Artefatos avaliados**           | ( ) Diagrama HTA   ( ) Modelo GOMS   ( X ) Ambos                                                                           |
| **Link Perfil de Usuário Alvo**   | [Perfil de Usuário 1](../../../../analiseRequisitos/perfilUsuario/perfilUsuario1)                                            |
| **Link para o diagrama HTA**      | [Analise HTA](../../../../analiseRequisitos/analiseTarefas/HTA/HTAPersona2)                                                |
| **Link para o modelo GOMS**       | [Analise GOMS](../../../../analiseRequisitos/analiseTarefas/HTA/GOMSPersona2)                                              |

<font size="3"><p class="table-source">Fonte: [Breno Teixeira](https://github.com/brenolteixeira).</p></font>

<font size="3"><p class="table-source"><b>Tabela 3</b> - Funcionalidade: Solicitação Urgente de Bolsa de Sangue Fenotipado </p></font>

| Campo                             |Informação                                                                                                                  |
|:----------------------------------|:---------------------------------------------------------------------------------------------------------------------------|
| **Funcionalidade**                | Solicitação Urgente de Bolsa de Sangue Fenotipado                                                                                             |
| **Artefatos avaliados**           | ( ) Diagrama HTA   ( ) Modelo GOMS   ( X ) Ambos                                                                           |
| **Link Perfil de Usuário Alvo**   | [Perfil de Usuário 2](../../../../analiseRequisitos/perfilUsuario/perfilUsuario2)                                            |
| **Link para o diagrama HTA**      | [Analise HTA](../../../../analiseRequisitos/analiseTarefas/HTA/HTAPersona3)                                                |
| **Link para o modelo GOMS**       | [Analise GOMS](../../../../analiseRequisitos/analiseTarefas/HTA/GOMSPersona3)                                              |

<font size="3"><p class="table-source">Fonte: [Pedro Lucas](https://github.com/Pwdrinho).</p></font>

<font size="3"><p class="table-source"><b>Tabela 4</b> - Funcionalidade: Notificar Reação Transfusional (FIRT Digital)</p></font>

| Campo                             |Informação                                                                                                                  |
|:----------------------------------|:---------------------------------------------------------------------------------------------------------------------------|
| **Funcionalidade**                | Notificar Reação Transfusional (FIRT Digital)                                                                                             |
| **Artefatos avaliados**           | ( ) Diagrama HTA   ( ) Modelo GOMS   ( X ) Ambos                                                                           |
| **Link Perfil de Usuário Alvo**   | [Perfil de Usuário 2](../../../../analiseRequisitos/perfilUsuario/perfilUsuario2)                                            |
| **Link para o diagrama HTA**      | [Analise HTA](../../../../analiseRequisitos/analiseTarefas/HTA/HTAPersona4)                                                |
| **Link para o modelo GOMS**       | [Analise GOMS](../../../../analiseRequisitos/analiseTarefas/HTA/GOMSPersona4)                                              |

<font size="3"><p class="table-source">Fonte: [Gabriel Diniz](https://github.com/GabrielDiniz12).</p></font>

<font size="3"><p class="table-source"><b>Tabela 5</b> - Funcionalidade: Emitir a Carteirinha de Identificação</p></font>

| Campo                             |Informação                                                                                                                  |
|:----------------------------------|:---------------------------------------------------------------------------------------------------------------------------|
| **Funcionalidade**                |  Emitir a Carteirinha de Identificação                                                                                |
| **Artefatos avaliados**           | ( ) Diagrama HTA   ( ) Modelo GOMS   ( X ) Ambos                                                                           |
| **Link Perfil de Usuário Alvo**   | [Perfil de Usuário 4](../../../../analiseRequisitos/perfilUsuario/perfilUsuario4)                                            |
| **Link para o diagrama HTA**      | [Analise HTA](../../../../analiseRequisitos/analiseTarefas/HTA/HTAPersona5)                                                |
| **Link para o modelo GOMS**       | [Analise GOMS](../../../../analiseRequisitos/analiseTarefas/HTA/GOMSPersona5)                                              |

<font size="3"><p class="table-source">Fonte: [Júlia Gabriella](https://github.com/juliagabriellafs).</p></font>

<font size="3"><p class="table-source"><b>Tabela 6</b> - Funcionalidade: Agendamento de HemoTour</p></font>

| Campo                             |Informação                                                                                                                  |
|:----------------------------------|:---------------------------------------------------------------------------------------------------------------------------|
| **Funcionalidade**                | Agendamento de HemoTour                                                                                            |
| **Artefatos avaliados**           | ( ) Diagrama HTA   ( ) Modelo GOMS   ( X ) Ambos                                                                           |
| **Link Perfil de Usuário Alvo**   | [Perfil de Usuário 4](../../../../analiseRequisitos/perfilUsuario/perfilUsuario4)                                            |
| **Link para o diagrama HTA**      | [Analise HTA](../../../../analiseRequisitos/analiseTarefas/HTA/HTAPersona6)                                                |
| **Link para o modelo GOMS**       | [Analise GOMS](../../../../analiseRequisitos/analiseTarefas/HTA/GOMSPersona6)                                              |

<font size="3"><p class="table-source">Fonte: [Lucas Oliveira](https://github.com/dev-LucasDpaula).</p></font>

<font size="3"><p class="table-source"><b>Tabela 7</b> - Funcionalidade: Triagem Digital (Sangria Terapêutica)</p></font>

| Campo                             |Informação                                                                                                                  |
|:----------------------------------|:---------------------------------------------------------------------------------------------------------------------------|
| **Funcionalidade**                | Triagem Digital (Sangria Terapêutica)                                                                                           |
| **Artefatos avaliados**           | ( ) Diagrama HTA   ( ) Modelo GOMS   ( X ) Ambos                                                                           |
| **Link Perfil de Usuário Alvo**   | [Perfil de usuário 3](../../../../analiseRequisitos/elencoPersonas.md)                                                      |
| **Link para o diagrama HTA**      | [Analise HTA](../../../../analiseRequisitos/analiseTarefas/HTA/HTAPersona7.md)                                             |
| **Link para o modelo GOMS**       | [Analise GOMS](../../../../analiseRequisitos/analiseTarefas/GOMS/GOMSPersona7.md)                                          |

<font size="3"><p class="table-source">Fonte: [Pedro Ian](https://github.com/pedroiaan).</p></font>


---

## 3. Seleção dos Participantes

### Expectativa — Perfil Planejado

Conforme definido no Planejamento da Avaliação o participante deveria apresentar características condizentes com o Perfil de Usuário Alvo da funcionalidade avaliada, considerando fatores como: faixa etária, grau de familiaridade com tecnologia e vínculo com os serviços da FHB.

<font size="3"><p class="table-source"><b>Tabela 8</b> - Entrevista 1</p></font>

| Critério de Seleção              | Descrição Planejada                                                                                                          |
|:---------------------------------|:-----------------------------------------------------------------------------------------------------------------------------|
| **Faixa etária**                 | 18 a 40 anos                                                                                                                 |
| **Vínculo com a FHB**            | Doador de sangue voluntário", "Paciente em acompanhamento" e "Responsável por paciente"                                      |
| **Familiaridade com tecnologia** | Usuário com afinidade com tecnologia                                                                                         |
| **Quantidade planejada**         | 2 participantes                                                                                                              |
| **Justificativa**                | Os perfis selecionados possuem afinidade com os usuários alvo das funcionalidades pela faixa etária, nível afinidade, etc.   |

<font size="3"><p class="table-source">Fonte: [Breno Teixeira](https://github.com/Brenolteixeira) , [Júlia Gabriella](https://github.com/juliagabriellafs) e [Pedro Américo](https://github.com/dev-americo).</p></font>

<font size="3"><p class="table-source"><b>Tabela 9</b> - Entrevista 2</p></font>

| Critério de Seleção              | Descrição Planejada                                                                                                          |
|:---------------------------------|:-----------------------------------------------------------------------------------------------------------------------------|
| **Faixa etária**                 | 25 a 52 anos                                                                                                               |
| **Vínculo com a FHB**            | Médicos(as) e/ou enfermeiros(as) hematologistas e/ou hemoterapeutas                                      |
| **Familiaridade com tecnologia** | Usuário com afinidade com tecnologia                                                                                         |
| **Quantidade planejada**         | 1 participantes                                                                                                              |
| **Justificativa**                | O participante possue experiência na área e afinidade com tecnologia, contribuindo para uma avaliação mais adequada das funcionalidades do sistema.   |

<font size="3"><p class="table-source">Fonte: [Pedro Lucas](https://github.com/Pwdrinho) e [Gabriel Diniz](https://github.com/GabrielDiniz12).</p></font>

<font size="3"><p class="table-source"><b>Tabela 10</b> - Entrevista 3</p></font>

| Critério de Seleção              | Descrição Planejada                                                                                                          |
|:---------------------------------|:-----------------------------------------------------------------------------------------------------------------------------|
| **Faixa etária**                 | 60 anos ou mais                                                                                                              |
| **Vínculo com a FHB**            | Usuário de exceção buscando atendimento de Sangria Terapêutica                                                               |
| **Familiaridade com tecnologia** | Letramento digital básico / baixa familiaridade                                                                              |
| **Quantidade planejada**         | 1 participante                                                                                                               |
| **Justificativa**                | Validar a clareza e a tolerância a erros do fluxo de tratamento de exceção projetado para o perfil de pessoa idosa.        |

<font size="3"><p class="table-source">Fonte: [Pedro Ian](https://github.com/pedroiaan).</p></font>

<font size="3"><p class="table-source"><b>Tabela 11</b> - Entrevista 4</p></font>

| Critério de Seleção              | Descrição Planejada                                                                                                          |
|:---------------------------------|:-----------------------------------------------------------------------------------------------------------------------------|
| **Faixa etária**                 | 40 a 50 anos                                                                                                                 |
| **Vínculo com a FHB**            | "Responsável por terceiros", "Responsável pelo Agendamento do HemoTour" e "Responsável pela seleção de alunos e seus respectivos fomulários  de autorização"                                      |
| **Familiaridade com tecnologia** | Usuário média afinidade com a técnologia                                                                                        |
| **Quantidade planejada**         | 1 participante                                                                                                           |
| **Justificativa**                | Os perfis selecionados possuem afinidade com os usuários alvo das funcionalidades pela faixa etária, nível afinidade, etc.   |

<font size="3"><p class="table-source">Fonte: [Lucas Oliveira](https://github.com/dev-LucasDpaula).</p></font>

---

### Realidade — Participante Efetivo

Tabela com a realidade dos participantes encontrados.

**Tabela 12** — Dados do participante entrevistado.

| Campo                             | Dado Coletado                                                                                                     |
|:----------------------------------|:------------------------------------------------------------------------------------------------------------------|
| **Nome / Identificação**          | Enzo Menali                                                  |
| **Faixa etária**                  | 20                                                                                                      |
| **Vínculo com a FHB**             | Doador  |
| **Familiaridade com tecnologia**  | Alta |
| **O perfil atende ao planejado?** | (X) Sim   ( ) Parcialmente   ( ) Não — Justificativa:  |

<font size="3"><p class="table-source">Fonte: [Pedro Américo](https://github.com/dev-americo).</p></font>

**Tabela 13** — Dados do participante entrevistado.

| Campo                             | Dado Coletado                                                                                                     |
|:----------------------------------|:------------------------------------------------------------------------------------------------------------------|
| **Nome / Identificação**          | Paulo Vitor                                              |
| **Faixa etária**                  | 20                                                                                                      |
| **Vínculo com a FHB**             | Auxilia Familiar com Hemofilia B grave a utilizar o portal  |
| **Familiaridade com tecnologia**  | Alta |
| **O perfil atende ao planejado?** | ( ) Sim   (X) Parcialmente   ( ) Não — Justificativa: Atende ao perfil adotado no projeto, dada a vivência e o acompanhamento do familiar com Hemofilia B grave.  |

<font size="3"><p class="table-source">Fonte: [Breno Teixeira](https://github.com/brenolteixeira).</p></font>



**Tabela 14** — Dados do participante entrevistado.

| Campo                             | Dado Coletado                                                                                                     |
|:----------------------------------|:------------------------------------------------------------------------------------------------------------------|
| **Nome / Identificação**          | NM                                                    |
| **Faixa etária**                  | 25                                                                                                       |
| **Vínculo com a FHB**             | A participante estudou e realizou pesquisa acadêmicas sobre o FHB e algumas de suas funcionalidades  |
| **Familiaridade com tecnologia**  | A participante informou ter uma familiaridade "normal" com a tecnologia, é uma usuária comum |
| **O perfil atende ao planejado?** | (X) Sim   ( ) Parcialmente   ( ) Não — Justificativa: A participante atende ao planejado por ter tido contato com a tecnologia e perfil semelhante ao dos trabalhadores da área |

<font size="3"><p class="table-source">Fonte: [Pedro Lucas](https://github.com/Pwdrinho) e [Gabriel Diniz](https://github.com/GabrielDiniz12).</p></font>

**Tabela 15** — Dados do participante entrevistado.

| Campo                             | Dado Coletado                                                                                                     |
|:----------------------------------|:------------------------------------------------------------------------------------------------------------------|
| **Nome / Identificação**          | Enzo Menali                                                  |
| **Faixa etária**                  | 20                                                                                                      |
| **Vínculo com a FHB**             | Doador  |
| **Familiaridade com tecnologia**  | Alta |
| **O perfil atende ao planejado?** | (X) Sim   ( ) Parcialmente   ( ) Não — Justificativa:  |

<font size="3"><p class="table-source">Fonte: [Júlia Gabriella](https://github.com/juliagabriellafs).</p></font>

**Tabela 16** — Dados do participante entrevistado.

| Campo                             | Dado Coletado                                                                                                     |
|:----------------------------------|:------------------------------------------------------------------------------------------------------------------|
| **Nome / Identificação**          | Alessandro de Paula Silva |
| **Faixa etária**                  | 25                                                                                                      |
| **Vínculo com a FHB**             | Professor com a vontade de realizar um agendamento de HemoTour |
| **Familiaridade com tecnologia**  | Média |
| **O perfil atende ao planejado?** | (X) Sim   ( ) Parcialmente   ( ) Não — Justificativa:  |

<font size="3"><p class="table-source">Fonte: [Lucas Oliveira](https://github.com/dev-LucasDpaula).</p></font>

**Tabela 17** — Dados do participante entrevistado.

| Campo                             | Dado Coletado                                                                                                     |
|:----------------------------------|:------------------------------------------------------------------------------------------------------------------|
| **Nome / Identificação**          | Jocilia                                         |
| **Faixa etária**                  | 70                                                                                                      |
| **Vínculo com a FHB**             | Doador  |
| **Familiaridade com tecnologia**  | Baixa |
| **O perfil atende ao planejado?** | (X) Sim   ( ) Parcialmente   ( ) Não — Justificativa:  |

<font size="3"><p class="table-source">Fonte: [Pedro Ian](https://github.com/pedroiaan).</p></font>

---

## 4. Lista de Problemas Encontrados

Esta seção registra os problemas, erros e inconsistências identificados nos artefatos de Análise de Tarefas pelo participante ou observados pelo entrevistador durante a sessão. Cada problema deve ser descrito de forma objetiva, indicando em qual passo ou subtarefa do diagrama ele se manifesta, qual é a natureza do erro e qual o seu grau de impacto na fidelidade e na utilidade do artefato para o projeto.

A **escala de gravidade**, adaptada ao contexto de avaliação de artefatos de Análise de Tarefas:

| Nível | Classificação  | Critério                                                                                                       |
|:-----:|:---------------|:---------------------------------------------------------------------------------------------------------------|
| **1** | Cosmético      | Não compromete a compreensão do fluxo; melhoria apenas de nomenclatura, formatação ou granularidade estética   |
| **2** | Pequeno        | Causa confusão pontual em uma subtarefa, mas o fluxo geral permanece compreensível                             |
| **3** | Grande         | Compromete significativamente a compreensão de uma etapa da tarefa ou da lógica de sequência do diagrama       |
| **4** | Catastrófico   | Torna o diagrama incoerente com a realidade da tarefa ou impede seu uso como base para o design                |

### Modelo de tabela

Tabela modelo do que foi realmente encontrado nas entrevistas.

**Tabela X** — Problemas identificados na avaliação dos artefatos de Análise de Tarefas.

| ID  | Artefato       | Passo / Subtarefa Afetada                  | Descrição do Erro ou Dificuldade                                              | Gravidade (1–4) | Natureza do Erro                                                                 | Sugestão de Correção no Diagrama                                          |
|:---:|:--------------:|:-------------------------------------------|:------------------------------------------------------------------------------|:---------------:|:---------------------------------------------------------------------------------|:--------------------------------------------------------------------------|
| E0X | `( ) HTA  ( ) GOMS` | `[Subtarefa X.X]` | `[DESCREVA O PROBLEMA]` | `[1/2/3/4]` | `[MARCAR A NATUREZA]` | `[INSERIR]`  |

<font size="3"><p class="table-source">Fonte: [Pedro Lucas](https://github.com/Pwdrinho) e [Gabriel Diniz](https://github.com/GabrielDiniz12).</p></font>

<!-- | ID  | Artefato       | Passo / Subtarefa Afetada                  | Descrição do Erro ou Dificuldade                                              | Gravidade (1–4) | Natureza do Erro                                                                 | Sugestão de Correção no Diagrama                                          |
|:---:|:--------------:|:-------------------------------------------|:------------------------------------------------------------------------------|:---------------:|:---------------------------------------------------------------------------------|:--------------------------------------------------------------------------|
| E01 | `( ) HTA  ( ) GOMS` | `[ex.: Subtarefa 2.1 — Selecionar horário]` | `[DESCREVA O PROBLEMA — ex.: "O participante indicou que esta etapa não existe no fluxo real; o sistema já pré-seleciona o horário automaticamente"]` | `[1/2/3/4]` | `( ) Subtarefa inexistente na realidade` `( ) Etapa ausente no diagrama` `( ) Sequência incorreta` `( ) Notação errada` `( ) Nomenclatura confusa` `( ) Granularidade inadequada` | `[INSERIR — ex.: "Remover a subtarefa 2.1 e atualizar o plano de sequência do nó 2"]` |
| E02 | `( ) HTA  ( ) GOMS` | `[Subtarefa X.X]`                           | `[DESCREVA O PROBLEMA]`                                                        | `[1/2/3/4]`     | `[MARCAR A NATUREZA]`                                                            | `[INSERIR]`                                                               |
| E03 | `( ) HTA  ( ) GOMS` | `[Subtarefa X.X]`                           | `[DESCREVA O PROBLEMA]`                                                        | `[1/2/3/4]`     | `[MARCAR A NATUREZA]`                                                            | `[INSERIR]`                                                               |
| —   | —              | —                                          | *Adicione linhas conforme necessário*                                         | —               | —                                                                                | —                                                                         | -->

---

## 5. Feedback dos Usuários

Esta seção registra as percepções, opiniões e comentários espontâneos expressos pelo participante ao longo da entrevista — especialmente aqueles verbalizados durante o protocolo Think Aloud. O objetivo é preservar a voz do usuário como insumo qualitativo para o reprojeto dos artefatos, capturando tanto críticas quanto validações do fluxo modelado.

### Modelo de tabela

Modelo de tabela para a transcrição do feedback dos usuários

**Tabela X** — Feedback do participante durante a avaliação da Análise de Tarefas.

| Momento da Entrevista                     | Fala ou Percepção do Participante                                                                                                  | Natureza           |
|:------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------|:------------------:|
| Descrição do momento na entrevista | `( ) Crítica  () Validação  ( ) Sugestão  ( ) Dúvida` |


<font size="3"><p class="table-source">Fonte: [Pedro Lucas](https://github.com/Pwdrinho) e [Gabriel Diniz](https://github.com/GabrielDiniz12).</p></font>

---

## 6. Análise e Interpretação dos Resultados

Após a coleta e o registro dos dados, o grupo deve realizar uma análise dos resultados obtidos, buscando responder às perguntas definidas no Planejamento da Avaliação. A interpretação deve considerar:

- **Fidedignidade dos artefatos:** Os diagramas HTA e os modelos GOMS refletem com precisão o fluxo real da tarefa, conforme percebido pelo participante? Há distâncias significativas entre o modelo produzido e a realidade do usuário?
- **Confiabilidade dos dados:** O participante recrutado corresponde ao Perfil de Usuário Alvo? Fatores contextuais (nervosismo, pouca familiaridade com leitura de diagramas, ambiente inadequado) podem ter distorcido as respostas?
- **Validade interna:** As perguntas do roteiro e o protocolo Think Aloud foram eficazes para revelar os problemas reais nos artefatos, ou há aspectos da modelagem que não foram cobertos pela avaliação?
- **Padrões e recorrências:** Alguma subtarefa ou nível de decomposição gerou confusão de forma consistente? O participante validou a estrutura geral do diagrama ou questionou aspectos fundamentais do fluxo?
- **Impacto no projeto:** Como os problemas identificados afetam a validade dos artefatos como base para o design das próximas etapas? Quais correções são prioritárias antes do avanço para a prototipação?

Os resultados individuais de cada entrevista serão posteriormente consolidados em uma análise interparticipante pelo grupo, identificando padrões comuns de erro ou validação entre todos os artefatos de Análise de Tarefas avaliados.

---

## 7. Planejamento de Reprojeto

Conforme [Barbosa e Silva (2021)](#ref1), as inconsistências e os problemas identificados durante a avaliação devem ser corrigidos nos artefatos por meio de um reprojeto orientado pelos dados coletados. O reprojeto **deve preservar a estrutura e a intenção original do diagrama**, realizando apenas as alterações necessárias para corrigir os erros identificados.

**Tabela X** — Cronograma de reprojeto dos artefatos de Análise de Tarefas.

| Atividade de Reprojeto                                                                                          | Artefato       | Responsável                        | Data Prevista  |
|:----------------------------------------------------------------------------------------------------------------|:--------------:|:-----------------------------------|:--------------:|
| `[DESCREVA A ATIVIDADE]`                                                                                        | `( ) HTA  ( ) GOMS` | `[Nome do integrante responsável]` | `[DD/MM/AAAA]` |

<font size="3"><p class="table-source">Fonte: [Lucas Oliveira](https://github.com/dev-LucasDpaula) e [Pedro Ian](https://github.com/pedroiaan).</p></font>

---

## Referências Bibliográficas

<a id="ref1"></a>
> BARBOSA, S. D. J.; SILVA, B. S.; SILVEIRA, M. S.; GASPARINI, I.; DARIN, T.; BARBOSA, G. D. J. **Interação Humano-Computador e Experiência do Usuário**. Autopublicação, 2021.

---

## Histórico de Versões
| Versão | Descrição | Data | Autor(es) | Data de revisão | Revisor(es) |
| :---: | :--- | :---: | :---: | :---: | :---: |
| 1.0 | Criação do documento | 19/05/2026 | [Pedro Americo](https://github.com/dev-americo) | 19/05/2026 | [Breno Teixeira](https://github.com/BrenoLTeixeira)|
| 1.1 | inserção funcionalidade 2 | 19/05/2026 | [Breno Teixeira](https://github.com/BrenoLTeixeira) | 19/05/2026 | [Gabriel Diniz](https://github.com/GabrielDiniz12)|
| 1.2 | inserção funcionalidade 4 | 19/05/2026 | [Gabriel Diniz](https://github.com/GabrielDiniz12) | 19/05/2026 | [Julia Gabriella](https://github.com/juliagabriellafs)|
| 1.3 | inserção funcionalidade 5 | 19/05/2026 | [Julia Gabriella](https://github.com/juliagabriellafs) | 19/05/2026 | [Lucas Oliveira](https://github.com/dev-LucasDpaula) |
| 1.4 | inserção funcionalidade 6 | 19/05/2026 | [Lucas Oliveira](https://github.com/dev-LucasDpaula) | 19/05/2026 | [Pedro Ian](https://github.com/pedroiaan)|
| 1.5 | inserção funcionalidade 7 | 19/05/2026 | [Pedro Ian](https://github.com/pedroiaan) | 19/05/2026 | [Pedro Lucas](https://github.com/Pwdrinho) |
| 1.6 | inserção funcionalidade 3 | 19/05/2026 | [Pedro Lucas](https://github.com/Pwdrinho) | 19/05/2026 | [Pedro Americo](https://github.com/dev-americo) |
| 1.7 | Adição participante NM | 22/05/2026 | [Gabriel Diniz](https://github.com/GabrielDiniz12) e [Pedro Lucas](https://github.com/Pwdrinho) | 22/05/2026 | [Julia Gabriella](https://github.com/juliagabriellafs)|
| 1.8 | Correção na tabela 7 | 29/05/2026 | [Gabriel Diniz](https://github.com/GabrielDiniz12) | 29/05/2026 | [Julia Gabriella](https://github.com/juliagabriellafs)|
| 1.9 | Adiciona a realidade de todos os participantes | 03/06/2026 | [Gabriel Diniz](https://github.com/GabrielDiniz12) | 03/06/2026 | [Lucas Oliveira](https://github.com/dev-LucasDpaula)|
| 2.0 | Atualizações e correções | 23/06/2026 | [Julia Gabriella](https://github.com/juliagabriellafs) | 23/06/2026 | [Lucas Oliveira](https://github.com/dev-LucasDpaula) |
| 2.1 | inserção tabela de contribuição e correções em fontes | 01/07/2026 | [Gabriel Diniz](https://github.com/GabrielDiniz12) | 01/07/2026 | [Breno Teixeira](https://github.com/BrenoLTeixeira)|
