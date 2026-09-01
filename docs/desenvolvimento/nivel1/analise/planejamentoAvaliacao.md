# Planejamento da Avaliação da Análise de Tarefas

### Tabela de Contribuição

| Integrante | Tópicos de Contribuição |
| :--- | :--- |
| [Breno Teixeira](https://github.com/BrenoLTeixeira) | Introdução<br>D — Determinar os Objetivos<br>Funcionalidade 2<br>Roteiro de Perguntas<br> |
| [Gabriel Diniz](https://github.com/GabrielDiniz12) | E — Explorar as Perguntas a Serem Respondidas<br>Funcionalidade 4<br>Cronograma das Entrevistas<br>Roteiro de Perguntas<br>Recrutamento dos Participantes<br> |
| [Júlia Gabriella](https://github.com/juliagabriellafs) | C — Escolher os Métodos de Avaliação<br>Funcionalidade 5<br>Preparação e Custos<br>|
| [Lucas Oliveira](https://github.com/dev-LucasDpaula) | Recrutamento dos Participantes<br>Funcionalidade 6<br>Cronograma das Entrevistas<br>Roteiro de Perguntas |
| [Pedro Américo](https://github.com/dev-americo) | Funcionalidade 1<br>Cronograma das Entrevistas<br>Roteiro de Perguntas<br>Teste Piloto 1<br>Recrutamento dos Participantes<br> |
| [Pedro Ian](https://github.com/pedroiaan) | D — Decidir como Lidar com as Questões Éticas<br>Funcionalidade 7<br>Cronograma das Entrevistas<br>Roteiro de Perguntas<br>Teste Piloto 2<br>Recrutamento dos Participantes<br> |
| [Pedro Lucas](https://github.com/Pwdrinho) | E — Avaliar, Interpretar e Apresentar os Dados<br>Referências Bibliográficas<br>Funcionalidade 3<br>Roteiro de Perguntas |

## Introdução

A avaliação da Análise de Tarefas é uma etapa essencial para garantir que os artefatos produzidos — diagramas **HTA (Hierarchical Task Analysis)** e modelos **GOMS (Goals, Operators, Methods and Selection Rules)** — representem com fidelidade e precisão as tarefas que os usuários do portal da **Fundação Hemocentro de Brasília (FHB)** precisam executar. Uma análise bem avaliada reduz o risco de projetar fluxos de interação desalinhados com a realidade dos usuários, evitando retrabalho nas etapas subsequentes do processo de design.

Para conduzir esse planejamento de forma estruturada, foi adotado o **framework DECIDE**, apresentado por [Barbosa e Silva (2021)](#ref1). Cada letra da sigla corresponde a uma atividade do planejamento, conforme a Tabela 1.

**Tabela 1** — Atividades do framework DECIDE e seus significados.

| Letra | Atividade                                              |
|:-----:|:-------------------------------------------------------|
| **D** | Determinar os objetivos da avaliação                   |
| **E** | Explorar as perguntas a serem respondidas              |
| **C** | Escolher os métodos de avaliação a serem utilizados    |
| **I** | Identificar e administrar as questões práticas         |
| **D** | Decidir como lidar com as questões éticas              |
| **E** | Avaliar, interpretar e apresentar os dados             |

*Fonte: Barbosa e Silva (2021).*

---

## D — Determinar os Objetivos

A avaliação tem como **objetivo geral** verificar e validar os artefatos de Análise de Tarefas produzidos para as funcionalidades propostas no portal da FHB, assegurando que os diagramas HTA e os modelos GOMS sejam tecnicamente corretos, coerentes com a realidade dos usuários do Hemocentro e adequados para fundamentar as próximas etapas do processo de design.

De forma mais específica, a avaliação busca:

- **Verificar a correção técnica dos artefatos:** confirmar se os diagramas HTA apresentam notação correta (decomposição hierárquica, planos de sequência, legendas e representação em tabela) e se os modelos GOMS estão estruturados de forma consistente com os objetivos, operadores e métodos definidos;
- **Validar a aderência à realidade dos usuários:** verificar, junto a participantes com o perfil de usuário adequado, se a sequência de subtarefas modelada nos diagramas corresponde ao modo como os usuários realmente executam — ou esperam executar — as atividades no contexto do Hemocentro;
- **Identificar inconsistências, omissões ou alternativas de design:** elicitar, a partir da perspectiva do usuário, problemas não identificados durante a produção dos artefatos, bem como fluxos alternativos que possam aprimorar a modelagem.

---

## E — Explorar as Perguntas a Serem Respondidas

Com base nos objetivos definidos, foram elaboradas as seguintes perguntas a serem respondidas ao longo da avaliação. Elas estão organizadas por dimensão de análise e devem orientar tanto o roteiro de entrevista quanto a interpretação dos dados coletados.

**Dimensão 1 — Correção técnica dos artefatos:**

1. O diagrama HTA apresenta a decomposição hierárquica das tarefas com as notações corretas (numeração de subtarefas, planos de sequência, condições de parada e legenda completa)?
2. A representação em tabela do HTA está coerente com o diagrama gráfico correspondente, sem discrepâncias de numeração, descrição ou ordem das subtarefas?
3. O modelo GOMS está estruturado de forma completa, com objetivos, operadores, métodos e regras de seleção claramente definidos para a funcionalidade avaliada?

**Dimensão 2 — Aderência à realidade dos usuários:**

4. A sequência de subtarefas modelada no diagrama HTA condiz com o modo como um usuário típico do Hemocentro executaria essa tarefa no portal — sem saltos ilógicos, redundâncias ou etapas incompreensíveis?
5. Os objetivos e os métodos definidos no modelo GOMS correspondem às metas e estratégias reais que um usuário adotaria ao interagir com o sistema?
6. Há alguma subtarefa modelada que, na visão do participante, não ocorreria na prática, ou alguma etapa relevante que esteja ausente nos artefatos?

**Dimensão 3 — Alternativas e melhorias:**

7. O participante consegue identificar um fluxo alternativo — mais eficiente ou mais natural — para realizar a mesma tarefa, que não esteja contemplado no diagrama atual?
8. Há sugestões de melhoria para a estrutura, a nomenclatura ou a granularidade das subtarefas modeladas?

---

## C — Escolher os Métodos de Avaliação

Para responder às perguntas definidas e atingir os objetivos desta avaliação, serão utilizados dois métodos combinados: **entrevista semiestruturada** e **observação com protocolo Think Aloud**.

**Entrevista semiestruturada:** O entrevistador conduzirá o participante por um roteiro de perguntas baseado nas dimensões definidas na seção **E**, apresentando os diagramas HTA e os modelos GOMS da funcionalidade avaliada. O participante será encorajado a analisar os artefatos criticamente, confrontando a sequência de tarefas modelada com sua experiência real ou esperada como usuário dos serviços da FHB.

**Observação com Think Aloud:** Durante a apresentação dos artefatos, o participante será solicitado a verbalizar seus pensamentos em voz alta — descrevendo o que compreende, o que questiona e o que modificaria em cada etapa da análise. O anotador registrará todas as verbalizações relevantes para análise posterior.

A escolha dessa combinação se justifica pelos seguintes fatores:

- A entrevista semiestruturada permite coletar dados ricos e aprofundados sobre a percepção do participante quanto à correção e à aderência dos diagramas, com baixo custo operacional;
- O Think Aloud fornece evidências espontâneas sobre pontos de confusão ou discordância que o participante poderia não mencionar em respostas diretas;
- A combinação dos dois métodos produz dados mais robustos e complementares do que cada um isoladamente (Barbosa e Silva, 2021).

Toda sessão deverá ser **gravada e documentada** de acordo com os procedimentos descritos na seção de questões práticas.

---

## I — Identificar as Questões Práticas da Avaliação

### Funcionalidade Avaliada

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
| **Funcionalidade**                |Solicitar dispensação domiciliar de medicação                                                                                             |
| **Artefatos avaliados**           | ( ) Diagrama HTA   ( ) Modelo GOMS   ( X ) Ambos                                                                           |
| **Link Perfil de Usuário Alvo**   | [Perfil de Usuário 1](../../../../analiseRequisitos/perfilUsuario/perfilUsuario1)                                            |
| **Link para o diagrama HTA**      | [Analise HTA](../../../../analiseRequisitos/analiseTarefas/HTA/HTAPersona2)                                                |
| **Link para o modelo GOMS**       | [Analise GOMS](../../../../analiseRequisitos/analiseTarefas/HTA/GOMSPersona2)                                              |

<font size="3"><p class="table-source">Fonte: [Breno Teixeira](https://github.com/Brenolteixeira).</p></font>

<font size="3"><p class="table-source"><b>Tabela 3</b> - Funcionalidade: Solicitação Urgente de Bolsa de Sangue Fenotipado</p></font>

| Campo                             |Informação                                                                                                                  |
|:----------------------------------|:---------------------------------------------------------------------------------------------------------------------------|
| **Funcionalidade**                | Solicitação Urgente de Bolsa de Sangue Fenotipado                                                                          |
| **Artefatos avaliados**           | ( ) Diagrama HTA   ( ) Modelo GOMS   ( X ) Ambos                                                                           |
| **Link Perfil de Usuário Alvo**   | [Perfil de Usuário 2](../../../../analiseRequisitos/perfilUsuario/perfilUsuario2)                                          |
| **Link para o diagrama HTA**      | [Analise HTA](../../../../analiseRequisitos/analiseTarefas/HTA/HTAPersona3)                                              |
| **Link para o modelo GOMS**       | [Analise GOMS](../../../../analiseRequisitos/analiseTarefas/GOMS/GOMSPersona3)                                           |

<font size="3"><p class="table-source">Fonte: [Pedro Lucas](https://github.com/pwdrinho).</p></font>

<font size="3"><p class="table-source"><b>Tabela 4</b> - Funcionalidade: Notificar Reação Transfusional</p></font>

| Campo                             |Informação                                                                                                                  |
|:----------------------------------|:---------------------------------------------------------------------------------------------------------------------------|
| **Funcionalidade**                | Notificar Reação Transfusional                                                            |
| **Artefatos avaliados**           | ( ) Diagrama HTA   ( ) Modelo GOMS   ( X ) Ambos                                                                           |
| **Link Perfil de Usuário Alvo**   | [Perfil de Usuário 2](../../../../analiseRequisitos/perfilUsuario/perfilUsuario2)                                            |
| **Link para o diagrama HTA**      | [Analise HTA](../../../../analiseRequisitos/analiseTarefas/HTA/HTAPersona4)                                                |
| **Link para o modelo GOMS**       | [Analise GOMS](../../../../analiseRequisitos/analiseTarefas/HTA/GOMSPersona4)                                              |

<font size="3"><p class="table-source">Fonte: [Gabriel Diniz](https://github.com/GabrielDiniz12).</p></font>

<font size="3"><p class="table-source"><b>Tabela 5</b> - Funcionalidade: Emitir a Carteirinha de Identificação</p></font>

| Campo                             |Informação                                                                                                                  |
|:----------------------------------|:---------------------------------------------------------------------------------------------------------------------------|
| **Funcionalidade**                | Emitir a Carteirinha de Identificação (Doença Falciforme)                                                                  |
| **Artefatos avaliados**           | ( ) Diagrama HTA   ( ) Modelo GOMS   ( X ) Ambos                                                                           |
| **Link Perfil de Usuário Alvo**   | [Perfil de Usuário 4](../../../../analiseRequisitos/perfilUsuario/perfilUsuario4)                                            |
| **Link para o diagrama HTA**      | [Analise HTA](../../../../analiseRequisitos/analiseTarefas/HTA/HTAPersona5)                                                |
| **Link para o modelo GOMS**       | [Analise GOMS](../../../../analiseRequisitos/analiseTarefas/HTA/GOMSPersona5)                                              |

<font size="3"><p class="table-source">Fonte: [Júlia Gabriella](https://github.com/juliagabriellafs).</p></font>

<font size="3"><p class="table-source"><b>Tabela 6</b> - Funcionalidade: Agendamento do HemoTour</p></font>

| Campo                             |Informação                                                                                                                  |
|:----------------------------------|:---------------------------------------------------------------------------------------------------------------------------|
| **Funcionalidade**                | Agendamento do HemoTour                                                                                             |
| **Artefatos avaliados**           | ( ) Diagrama HTA   ( ) Modelo GOMS   ( X ) Ambos                                                                           |
| **Link Perfil de Usuário Alvo**   | [Perfil de Usuário 4](../../../../analiseRequisitos/perfilUsuario/perfilUsuario4)                                            |
| **Link para o diagrama HTA**      | [Analise HTA](../../../../analiseRequisitos/analiseTarefas/HTA/HTAPersona6)                                                |
| **Link para o modelo GOMS**       | [Analise GOMS](../../../../analiseRequisitos/analiseTarefas/HTA/GOMSPersona6)                                              |

<font size="3"><p class="table-source">Fonte: [Lucas Oliveira](https://github.com/dev-LucasDpaula).</p></font>


<font size="3"><p class="table-source"><b>Tabela 7</b> - Funcionalidade: Triagem Digital</p></font>

| Campo                             |Informação                                                                                                                  |
|:----------------------------------|:---------------------------------------------------------------------------------------------------------------------------|
| **Funcionalidade** | Triagem Digital (Sangria Terapêutica)                                                                                      |
| **Artefatos avaliados** | ( ) Diagrama HTA   ( ) Modelo GOMS   ( X ) Ambos                                                                           |
| **Link Perfil de Usuário Alvo** | [Elenco de Personas 3](../../../../analiseRequisitos/elencoPersonas.md)                                                      |
| **Link para o diagrama HTA** | [Analise HTA](../../../../analiseRequisitos/analiseTarefas/HTA/HTAPersona7.md)                                             |
| **Link para o modelo GOMS** | [Analise GOMS](../../../../analiseRequisitos/analiseTarefas/GOMS/GOMSPersona7.md)                                          |

<font size="3"><p class="table-source">Fonte: [Pedro Ian](https://github.com/pedroiaan).</p></font>

---

### Recrutamento dos Participantes

Para as funcionalidades da tabela 1, 2 e 4 utilizaremos o recrutamento de pessoas na própria universidade, o que se encaixa no perfil de usuário das funcionalidades de maneira plena ou ao menos parcial.

Para as funcionalidades das tabelas 3 e 4, buscaremos contato com pessoas da área de enfermagem, que possuem entendimento sobre os procedimentos a serem realizados nas funcionalidades.

Para a funcionalidade de Visitas Técnicas, será recrutado um profissional atuante na área da educação (como um professor ou coordenador escolar). Para a funcionalidade de Triagem Digital, o recrutamento focará especificamente em uma pessoa idosa com letramento digital básico, perfil ideal para validar a clareza e a tolerância a erros do fluxo de tratamento de exceção projetado.


---

### Preparação

O subgrupo entrevistador será responsável por conduzir as perguntas do roteiro, apresentar os artefatos ao participante e registrar as respostas e verbalizações coletadas. A sessão deverá envolver **no mínimo 2 (dois) integrantes do subgrupo**, com papéis bem definidos:

- **Integrante 1 — Entrevistador/Condutor:** responsável por apresentar os artefatos (diagramas HTA e modelos GOMS), conduzir as perguntas do roteiro, incentivar o Think Aloud e registrar as respostas por escrito;
- **Integrante 2 — Operador de câmera:** responsável por **segurar manualmente o celular** durante toda a sessão, posicionando-o de forma a capturar simultaneamente a **tela com os artefatos sendo apresentados e o áudio da conversa**.
- **Integrante 3 — Observador (Opicional):** responsável por anotar e auxiliar qualquer atividade necessária durante a seção de avaliação.

O entrevistador deverá apresentar os artefatos de forma progressiva — primeiro o diagrama geral, depois cada subtarefa individualmente — permitindo que o participante analise cada nível de decomposição antes de prosseguir. Em caso de discordância ou sugestão, o participante deverá ser incentivado a detalhar sua ideia verbalmente, e toda proposta de alteração deverá ser anotada para avaliação posterior pelo grupo.

---

### Custos

A realização das entrevistas não vai gerar custos para a equipe nem para os participantes. Para garantir isso, as entrevistas deverão ser conduzidas de forma **presencial**. Os equipamentos necessários serão exclusivamente dispositivos pessoais com câmera e microfone disponíveis.

Os materiais utilizados na entrevista serão:

- Diagrama HTA e/ou modelo GOMS da funcionalidade avaliada (impresso ou em tela);
- Roteiro de perguntas desta avaliação;
- Termo de Consentimento Livre e Esclarecido (TCLE);
- Registro em vídeo (celular segurado manualmente pelo integrante designado).

---

### Cronograma das Entrevistas

<font size="3"><p class="table-source"><b>Tabela 8</b> - Entrevista 1: Cronograma da entrevista de avaliação da Análise de Tarefas</p></font>

| Entrevistador(es) | Entrevistado | Perfil do Usuário | Data | Horário de Início | Horário de Fim | Local |
|:------------------|:-------------|:------------------|:----:|:-----------------:|:--------------:|:------|
| [Breno Teixeira](https://github.com/BrenoLTeixeira), [Julia Gabriella](https://github.com/juliagabriellafs) e [Pedro Américo](https://github.com/dev-americo) | Enzo Menali e Paulo Vitor | [Perfil de Usuário 1](../../../../analiseRequisitos/perfilUsuario/perfilUsuario1) [Perfil de Usuário 4](../../../../analiseRequisitos/perfilUsuario/perfilUsuario1) | 21/05/2026 | 14:00 | 14:30 | Presencial — FCTE |

<font size="3"><p class="table-source">Fonte: [Pedro Américo](https://github.com/dev-americo).</p></font>

<font size="3"><p class="table-source"><b>Tabela 9</b> - Entrevista 2: Cronograma da entrevista de avaliação da Análise de Tarefas</p></font>

| Entrevistador(es) | Entrevistado | Perfil do Usuário | Data | Horário de Início | Horário de Fim | Local |
|:------------------|:-------------|:------------------|:----:|:-----------------:|:--------------:|:------|
| [Gabriel Diniz](https://github.com/GabrielDiniz12) e [Pedro Lucas](https://github.com/Pwdrinho) | NM | [Perfil de Usuário 2](../../../../analiseRequisitos/perfilUsuario/perfilUsuario2)  | 22/05/2026 | 11:40 | 12:00 | Presencial — FCTE |

<font size="3"><p class="table-source">Fonte: [Gabriel Diniz](https://github.com/GabrielDiniz12).</p></font>

<font size="3"><p class="table-source"><b>Tabela 10</b> - Entrevista 3: Cronograma da entrevista de avaliação da Análise de Tarefas</p></font>

| Entrevistador(es) | Entrevistado | Perfil do Usuário | Data | Horário de Início | Horário de Fim | Local |
|:------------------|:-------------|:------------------|:----:|:-----------------:|:--------------:|:------|
| [Lucas Oliveira](https://github.com/dev-LucasDpaula) e [Pedro Ian](https://github.com/pedroiaan) | Jocilia | [Perfil de Usuário 3](../../../../analiseRequisitos/perfilUsuario/perfilUsuario4)  | 29/05/2026 | 15:00 | 15:30 | Presencial — Lucio Costa |

<font size="3"><p class="table-source">Fonte: [Pedro Ian](https://github.com/pedroiaan).</p></font>

<font size="3"><p class="table-source"><b>Tabela 11</b> - Entrevista 4: Cronograma da entrevista de avaliação da Análise de Tarefas</p></font>

| Entrevistador(es) | Entrevistado | Perfil do Usuário | Data | Horário de Início | Horário de Fim | Local |
|:------------------|:-------------|:------------------|:----:|:-----------------:|:--------------:|:------|
| [Lucas Oliveira](https://github.com/dev-LucasDpaula) e [Pedro Ian](https://github.com/pedroiaan) | Alessandro | [Perfil de Usuário 4](../../../../analiseRequisitos/perfilUsuario/perfilUsuario4)  | 29/05/2026 | 16:30 | 17:00 | Presencial — Aguas Claras |

<font size="3"><p class="table-source">Fonte: [Lucas Oliveira](https://github.com/dev-LucasDpaula).</p></font>

---

### Roteiro de Perguntas

A Tabela 3 apresenta o roteiro de perguntas que deverá ser aplicado ao participante durante a entrevista. As perguntas são baseadas nas questões definidas na seção **E** deste documento e devem ser realizadas na ordem apresentada. O entrevistador deve instigar o participante a detalhar suas respostas e a verbalizar seus pensamentos (Think Aloud) sempre que pertinente.

<font size="3"><p class="table-source"><b>Tabela 12</b> - Entrevista 4: Roteiro de perguntas para a avaliação da Análise de Tarefas</p></font>

| ID  | Enunciado da Pergunta                                                                                                                                           | Tipo de Resposta                                    |
|:---:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------|
| 1   | Qual é o seu grau de experiência com o uso de portais e sistemas web no geral?                                                                                  | Resposta discursiva                                 |
| 2   | Você já utilizou (ou tentou utilizar) o portal da Fundação Hemocentro de Brasília? Se sim, com qual finalidade?                                                 | Resposta discursiva                                 |
| 3   | Como você costuma realizar a tarefa de Doação em Grupo atualmente — seja pelo portal da FHB ou por outro meio?                                       | Resposta discursiva                                 |
| 4   | Observando o diagrama HTA apresentado, a sequência de subtarefas modelada é coerente com a forma como você realizaria essa tarefa? Se não, por quê?             | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Justificativa: __________ |
| 5   | Há alguma etapa presente no diagrama que, na sua opinião, não ocorreria na prática ou que não faria sentido nesse contexto?                                     | Resposta discursiva                                 |
| 6   | Há alguma etapa que você considera importante e que está ausente no diagrama HTA?                                                                               | Resposta discursiva                                 |
| 7   | A granularidade da decomposição está adequada? As subtarefas estão detalhadas o suficiente para ser compreendidas, sem estarem excessivamente fragmentadas?     | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Comentários: __________ |
| 8   | Os planos de sequência definidos no diagrama (ex.: executar A antes de B, ou A e B em qualquer ordem) refletem a realidade da tarefa?                           | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; O que mudaria? __________ |
| 9   | *(Aplicar apenas se o modelo GOMS foi produzido)* Os objetivos, operadores e métodos definidos no modelo GOMS correspondem ao que você faria ao usar o sistema? | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Observações: __________ |
| 10  | Você sugeriria algum fluxo alternativo para realizar essa tarefa que não esteja contemplado nos artefatos apresentados?                                         | Resposta discursiva                                 |
| 11  | De forma geral, os artefatos apresentados representam fielmente a tarefa Doação em Grupo como ela deveria funcionar no portal da FHB?                | ( ) Sim &nbsp;&nbsp; ( ) Parcialmente &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Justificativa: __________ |

<font size="3"><p class="table-source">Fonte: [Pedro Américo](https://github.com/dev-americo).</p></font>

<font size="3"><p class="table-source"><b>Tabela 13</b> - Entrevista 4: Roteiro de perguntas para a avaliação da Análise de Tarefas</p></font>

| ID  | Enunciado da Pergunta                                                                                                                                           | Tipo de Resposta                                    |
|:---:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------|
| 1   | Qual é o seu grau de experiência com o uso de portais e sistemas web no geral?                                                                                  | Resposta discursiva                                 |
| 2   | Você já utilizou (ou tentou utilizar) o portal da Fundação Hemocentro de Brasília? Se sim, com qual finalidade?                                                 | Resposta discursiva                                 |
| 3   | Como você costuma realizar a tarefa de Solicitar dispensação domiciliar de medicação atualmente — seja pelo portal da FHB ou por outro meio?                                       | Resposta discursiva                                 |
| 4   | Observando o diagrama HTA apresentado, a sequência de subtarefas modelada é coerente com a forma como você realizaria essa tarefa? Se não, por quê?             | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Justificativa: __________ |
| 5   | Há alguma etapa presente no diagrama que, na sua opinião, não ocorreria na prática ou que não faria sentido nesse contexto?                                     | Resposta discursiva                                 |
| 6   | Há alguma etapa que você considera importante e que está ausente no diagrama HTA?                                                                               | Resposta discursiva                                 |
| 7   | A granularidade da decomposição está adequada? As subtarefas estão detalhadas o suficiente para ser compreendidas, sem estarem excessivamente fragmentadas?     | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Comentários: __________ |
| 8   | Os planos de sequência definidos no diagrama (ex.: executar A antes de B, ou A e B em qualquer ordem) refletem a realidade da tarefa?                           | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; O que mudaria? __________ |
| 9   | *(Aplicar apenas se o modelo GOMS foi produzido)* Os objetivos, operadores e métodos definidos no modelo GOMS correspondem ao que você faria ao usar o sistema? | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Observações: __________ |
| 10  | Você sugeriria algum fluxo alternativo para realizar essa tarefa que não esteja contemplado nos artefatos apresentados?                                         | Resposta discursiva                                 |
| 11  | De forma geral, os artefatos apresentados representam fielmente a tarefa Solicitar dispensação domiciliar de medicação como ela deveria funcionar no portal da FHB?                | ( ) Sim &nbsp;&nbsp; ( ) Parcialmente &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Justificativa: __________ |

<font size="3"><p class="table-source">Fonte: [Breno Teixeira](https://github.com/Brenolteixeira).</p></font>

<font size="3"><p class="table-source"><b>Tabela 14</b> - Entrevista 2: Roteiro de perguntas para a avaliação da Análise de Tarefas</p></font>

| ID  | Enunciado da Pergunta                                                                                                                                           | Tipo de Resposta                                    |
|:---:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------|
| 1   | Qual é o seu grau de experiência com o uso de portais e sistemas web no geral?                                                                                  | Resposta discursiva                                 |
| 2   | Você já utilizou (ou tentou utilizar) o portal da Fundação Hemocentro de Brasília? Se sim, com qual finalidade?                                                 | Resposta discursiva                                 |
| 3   | Como você costuma realizar a tarefa de Solicitar dispensação domiciliar de medicação atualmente — seja pelo portal da FHB ou por outro meio?                                       | Resposta discursiva                                 |
| 4   | Observando o diagrama HTA apresentado, a sequência de subtarefas modelada é coerente com a forma como você realizaria essa tarefa? Se não, por quê?             | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Justificativa: __________ |
| 5   | Há alguma etapa presente no diagrama que, na sua opinião, não ocorreria na prática ou que não faria sentido nesse contexto?                                     | Resposta discursiva                                 |
| 6   | Há alguma etapa que você considera importante e que está ausente no diagrama HTA?                                                                               | Resposta discursiva                                 |
| 7   | A granularidade da decomposição está adequada? As subtarefas estão detalhadas o suficiente para ser compreendidas, sem estarem excessivamente fragmentadas?     | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Comentários: __________ |
| 8   | Os planos de sequência definidos no diagrama (ex.: executar A antes de B, ou A e B em qualquer ordem) refletem a realidade da tarefa?                           | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; O que mudaria? __________ |
| 9   | *(Aplicar apenas se o modelo GOMS foi produzido)* Os objetivos, operadores e métodos definidos no modelo GOMS correspondem ao que você faria ao usar o sistema? | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Observações: __________ |
| 10  | Você sugeriria algum fluxo alternativo para realizar essa tarefa que não esteja contemplado nos artefatos apresentados?                                         | Resposta discursiva                                 |
| 11  | De forma geral, os artefatos apresentados representam fielmente a tarefa Solicitação Urgente de Bolsa de Sangue Fenotipado como ela deveria funcionar no portal da FHB?                | ( ) Sim &nbsp;&nbsp; ( ) Parcialmente &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Justificativa: __________ |

<font size="3"><p class="table-source">Fonte: [Pedro Lucas](https://github.com/Pwdrinho).</p></font>


<font size="3"><p class="table-source"><b>Tabela 15</b> - Entrevista 2: Roteiro de perguntas para a avaliação da Análise de Tarefas</p></font>

| ID  | Enunciado da Pergunta                                                                                                                                           | Tipo de Resposta                                    |
|:---:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------|
| 1   | Qual é o seu grau de experiência com o uso de portais e sistemas web no geral?                                                                                  | Resposta discursiva                                 |
| 2   | Você já utilizou (ou tentou utilizar) o portal da Fundação Hemocentro de Brasília? Se sim, com qual finalidade?                                                 | Resposta discursiva                                 |
| 3   | Como você costuma realizar a tarefa de Solicitar dispensação domiciliar de medicação atualmente — seja pelo portal da FHB ou por outro meio?                                       | Resposta discursiva                                 |
| 4   | Observando o diagrama HTA apresentado, a sequência de subtarefas modelada é coerente com a forma como você realizaria essa tarefa? Se não, por quê?             | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Justificativa: __________ |
| 5   | Há alguma etapa presente no diagrama que, na sua opinião, não ocorreria na prática ou que não faria sentido nesse contexto?                                     | Resposta discursiva                                 |
| 6   | Há alguma etapa que você considera importante e que está ausente no diagrama HTA?                                                                               | Resposta discursiva                                 |
| 7   | A granularidade da decomposição está adequada? As subtarefas estão detalhadas o suficiente para ser compreendidas, sem estarem excessivamente fragmentadas?     | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Comentários: __________ |
| 8   | Os planos de sequência definidos no diagrama (ex.: executar A antes de B, ou A e B em qualquer ordem) refletem a realidade da tarefa?                           | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; O que mudaria? __________ |
| 9   | *(Aplicar apenas se o modelo GOMS foi produzido)* Os objetivos, operadores e métodos definidos no modelo GOMS correspondem ao que você faria ao usar o sistema? | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Observações: __________ |
| 10  | Você sugeriria algum fluxo alternativo para realizar essa tarefa que não esteja contemplado nos artefatos apresentados?                                         | Resposta discursiva                                 |
| 11  | De forma geral, os artefatos apresentados representam fielmente a tarefa Notificar Reação Transfusional como ela deveria funcionar no portal da FHB?                | ( ) Sim &nbsp;&nbsp; ( ) Parcialmente &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Justificativa: __________ |

<font size="3"><p class="table-source">Fonte: [Gabriel Diniz](https://github.com/GabrielDiniz12).</p></font>

<font size="3"><p class="table-source"><b>Tabela 16</b> - Entrevista 4: Roteiro de perguntas para a avaliação da Análise de Tarefas</p></font>

| ID  | Enunciado da Pergunta                                                                                                                                           | Tipo de Resposta                                    |
|:---:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------|
| 1   | Qual é o seu grau de experiência com o uso de portais e sistemas web no geral?                                                                                  | Resposta discursiva                                 |
| 2   | Você já utilizou (ou tentou utilizar) o portal da Fundação Hemocentro de Brasília? Se sim, com qual finalidade?                                                 | Resposta discursiva                                 |
| 3   | Como você costuma realizar a tarefa de Emitir a Carteirinha de Identificação  atualmente — seja pelo portal da FHB ou por outro meio?                                       | Resposta discursiva                                 |
| 4   | Observando o diagrama HTA apresentado, a sequência de subtarefas modelada é coerente com a forma como você realizaria essa tarefa? Se não, por quê?             | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Justificativa: __________ |
| 5   | Há alguma etapa presente no diagrama que, na sua opinião, não ocorreria na prática ou que não faria sentido nesse contexto?                                     | Resposta discursiva                                 |
| 6   | Há alguma etapa que você considera importante e que está ausente no diagrama HTA?                                                                               | Resposta discursiva                                 |
| 7   | A granularidade da decomposição está adequada? As subtarefas estão detalhadas o suficiente para ser compreendidas, sem estarem excessivamente fragmentadas?     | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Comentários: __________ |
| 8   | Os planos de sequência definidos no diagrama (ex.: executar A antes de B, ou A e B em qualquer ordem) refletem a realidade da tarefa?                           | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; O que mudaria? __________ |
| 9   | *(Aplicar apenas se o modelo GOMS foi produzido)* Os objetivos, operadores e métodos definidos no modelo GOMS correspondem ao que você faria ao usar o sistema? | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Observações: __________ |
| 10  | Você sugeriria algum fluxo alternativo para realizar essa tarefa que não esteja contemplado nos artefatos apresentados?                                         | Resposta discursiva                                 |
| 11  | De forma geral, os artefatos apresentados representam fielmente a tarefa "Emitir a Carteirinha de Identificação"  como ela deveria funcionar no portal da FHB?                | ( ) Sim &nbsp;&nbsp; ( ) Parcialmente &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Justificativa: __________ |

<font size="3"><p class="table-source">Fonte: [Pedro Américo](https://github.com/dev-americo).</p></font>

<font size="3"><p class="table-source"><b>Tabela 17</b> - Entrevista 4: Roteiro de perguntas para a avaliação da Análise de Tarefas</p></font>

| ID  | Enunciado da Pergunta                                                                                                                                           | Tipo de Resposta                                    |
|:---:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------|
| 1   | Qual é o seu grau de experiência com o uso de portais e sistemas web no geral?                                                                                  | Resposta discursiva                                 |
| 2   | Você já utilizou (ou tentou utilizar) o portal da Fundação Hemocentro de Brasília? Se sim, com qual finalidade?                                                 | Resposta discursiva                                 |
| 3   | Como você costuma realizar a tarefa de agendamento do HemoTour atualmente — seja pelo portal da FHB ou por outro meio?                                       | Resposta discursiva                                 |
| 4   | Observando o diagrama HTA apresentado, a sequência de subtarefas modelada é coerente com a forma como você realizaria essa tarefa? Se não, por quê?             | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Justificativa: __________ |
| 5   | Há alguma etapa presente no diagrama que, na sua opinião, não ocorreria na prática ou que não faria sentido nesse contexto?                                     | Resposta discursiva                                 |
| 6   | Há alguma etapa que você considera importante e que está ausente no diagrama HTA?                                                                               | Resposta discursiva                                 |
| 7   | A granularidade da decomposição está adequada? As subtarefas estão detalhadas o suficiente para ser compreendidas, sem estarem excessivamente fragmentadas?     | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Comentários: __________ |
| 8   | Os planos de sequência definidos no diagrama (ex.: executar A antes de B, ou A e B em qualquer ordem) refletem a realidade da tarefa?                           | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; O que mudaria? __________ |
| 9   | *(Aplicar apenas se o modelo GOMS foi produzido)* Os objetivos, operadores e métodos definidos no modelo GOMS correspondem ao que você faria ao usar o sistema? | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Observações: __________ |
| 10  | Você sugeriria algum fluxo alternativo para realizar essa tarefa que não esteja contemplado nos artefatos apresentados?                                         | Resposta discursiva                                 |
| 11  | De forma geral, os artefatos apresentados representam fielmente a tarefa agendamento do HemoTour como ela deveria funcionar no portal da FHB?                | ( ) Sim &nbsp;&nbsp; ( ) Parcialmente &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Justificativa: __________ |

<font size="3"><p class="table-source">Fonte: [Lucas Oliveira](https://github.com/dev-LucasDpaula).</p></font>

<font size="3"><p class="table-source"><b>Tabela 16</b> - Entrevista 7: Roteiro de perguntas para a avaliação da Análise de Tarefas</p></font>

| ID  | Enunciado da Pergunta                                                                                                                                           | Tipo de Resposta                                    |
|:---:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------|
| 1   | Qual é o seu grau de experiência com o uso de portais e sistemas web no geral?                                                                                  | Resposta discursiva                                 |
| 2   | Você já utilizou (ou tentou utilizar) o portal da Fundação Hemocentro de Brasília? Se sim, com qual finalidade?                                                 | Resposta discursiva                                 |
| 3   | Como você costuma realizar a tarefa de Triagem Digital (Sangria Terapêutica) atualmente — seja pelo portal da FHB ou por outro meio?                                       | Resposta discursiva                                 |
| 4   | Observando o diagrama HTA apresentado, a sequência de subtarefas modelada é coerente com a forma como você realizaria essa tarefa? Se não, por quê?             | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Justificativa: __________ |
| 5   | Há alguma etapa presente no diagrama que, na sua opinião, não ocorreria na prática ou que não faria sentido nesse contexto?                                     | Resposta discursiva                                 |
| 6   | Há alguma etapa que você considera importante e que está ausente no diagrama HTA?                                                                               | Resposta discursiva                                 |
| 7   | A granularidade da decomposição está adequada? As subtarefas estão detalhadas o suficiente para ser compreendidas, sem estarem excessivamente fragmentadas?     | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Comentários: __________ |
| 8   | Os planos de sequência definidos no diagrama (ex.: executar A antes de B, ou A e B em qualquer ordem) refletem a realidade da tarefa?                           | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; O que mudaria? __________ |
| 9   | *(Aplicar apenas se o modelo GOMS foi produzido)* Os objetivos, operadores e métodos definidos no modelo GOMS correspondem ao que você faria ao usar o sistema? | ( ) Sim &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Observações: __________ |
| 10  | Você sugeriria algum fluxo alternativo para realizar essa tarefa que não esteja contemplado nos artefatos apresentados?                                         | Resposta discursiva                                 |
| 11  | De forma geral, os artefatos apresentados representam fielmente a tarefa Triagem Digital (Sangria Terapêutica) como ela deveria funcionar no portal da FHB?                | ( ) Sim &nbsp;&nbsp; ( ) Parcialmente &nbsp;&nbsp; ( ) Não &nbsp;&nbsp; Justificativa: __________ |

<font size="3"><p class="table-source">Fonte: [Pedro Ian](https://github.com/pedroiaan).</p></font>

---

### Teste Piloto

Antes da realização das entrevistas oficiais, cada subgrupo deverá conduzir um **teste piloto** com o objetivo de avaliar o próprio planejamento. Conforme [Barbosa e Silva](#ref1), o teste piloto deve ser conduzido como se fosse uma sessão real de avaliação, permitindo verificar: (a) se a linguagem das perguntas é clara e objetiva; (b) se os artefatos apresentados (HTA e GOMS) são compreensíveis sem explicações adicionais excessivas; (c) se o tempo previsto para a sessão é adequado; e (d) se os equipamentos de registro estão funcionando corretamente.

<font size="3"><p class="table-source"><b>Vídeo 1</b> - Teste Piloto Analise de tarefas</p></font>

<div style="text-align: center;">
    <iframe width="100%" height="400" src="https://www.youtube.com/embed/X4L_23tcVbY" title="Entrega 4 - IHC - Grupo 4 - 2026.1" frameborder="0" allowfullscreen></iframe>
    <figcaption>
        Fonte: <a href="https://github.com/dev-americo">Pedro Americo</a> (2026).
        <a href="https://youtu.be/X4L_23tcVbY">Clique para assistir no YouTube</a>.
    </figcaption>
</div>

--- 
<font size="3"><p class="table-source"><b>Vídeo 2</b> - Teste Piloto Analise de tarefas</p></font>

<div style="text-align: center;">
    <iframe width="100%" height="400" src="https://www.youtube.com/embed/UmnLrXhbKVc" title="Teste Piloto   Analise de HTA e GOMS   2026 1   Grupo 4   funcionalidade 7" frameborder="0" allowfullscreen></iframe>
    <figcaption>
        Fonte: <a href="https://github.com/pedroiaan">Pedro Ian</a> (2026).
        <a href="https://youtu.be/UmnLrXhbKVc">Clique para assistir no YouTube</a>.
    </figcaption>
</div>

---

## D — Decidir como Lidar com as Questões Éticas

Toda avaliação que envolve a participação de pessoas deve ser conduzida com rigor ético. Neste projeto, as questões éticas são regidas pelos princípios da **autonomia, beneficência, não-maleficência, justiça e equidade** — conforme adotado pelo grupo em seu documento de Aspectos Éticos.

Antes do início de qualquer entrevista, o participante deverá receber, ler e assinar o **Termo de Consentimento Livre e Esclarecido (TCLE)** produzido pelo grupo. A assinatura do TCLE é condição obrigatória para o início da coleta de dados. Uma via assinada ficará com o participante e outra com o entrevistador.

O participante deve ser informado de que:

- Sua participação é **voluntária** e pode ser interrompida a qualquer momento, sem qualquer penalidade;
- Os dados coletados serão utilizados **exclusivamente para fins acadêmicos**, no âmbito da disciplina de Interação Humano-Computador;
- A entrevista **será gravada** apenas para fins de registro e análise interna do grupo, sendo garantido o sigilo de dados pessoais na publicação dos resultados.

---

## E — Avaliar, Interpretar e Apresentar os Dados

Após a realização das entrevistas, os dados coletados serão documentados e tratados de acordo com o contexto em que foram produzidos. O processo de análise seguirá as seguintes etapas:

**1. Registro e organização dos dados:** As respostas do participante e as verbalizações do Think Aloud serão transcritas a partir das gravações e organizadas com base no roteiro de perguntas (Tabela 3). Inconsistências, sugestões de alteração e fluxos alternativos apontados serão registrados separadamente para facilitar a priorização.

**2. Classificação dos problemas identificados:** Cada problema ou inconsistência detectado nos artefatos será classificado quanto à sua **natureza** (erro de notação, omissão de subtarefa, sequência incorreta, granularidade inadequada, nomenclatura confusa) e ao seu **impacto potencial** no redesign do portal (baixo, médio ou alto).

**3. Interpretação individual:** Cada subgrupo realizará uma análise dos dados coletados, buscando responder às perguntas definidas na seção **E** e determinar: quais elementos dos diagramas foram validados pelo participante; quais precisam de correção técnica; e quais requerem revisão estrutural antes do avanço para a etapa de prototipação.

**4. Consolidação interparticipante:** Os resultados individuais de todos os subgrupos serão consolidados pelo grupo em uma análise conjunta, identificando padrões recorrentes de erro ou validação que possam orientar uma revisão geral dos artefatos de Análise de Tarefas antes do avanço para o Nível 2 do processo de design.

**5. Critérios de confiabilidade:** Os dados serão julgados quanto ao seu grau de confiabilidade, considerando o perfil do participante, o contexto da entrevista e eventuais inconsistências nas respostas. Resultados obtidos com participantes que correspondem plenamente ao Perfil de Usuário Alvo terão peso maior na consolidação final.

**6. Apresentação ao grupo:** Os dados consolidados serão apresentados ao time de desenvolvimento por meio de um relato estruturado, contendo: um sumário dos dados coletados por funcionalidade, uma lista priorizada de problemas identificados nos artefatos e um conjunto de recomendações para a iteração e correção dos diagramas HTA e modelos GOMS.

---

## Referências Bibliográficas
<a id="ref1"></a>
> BARBOSA, S. D. J.; SILVA, B. S.; SILVEIRA, M. S.; GASPARINI, I.; DARIN, T.; BARBOSA, G. D. J. **Interação Humano-Computador e Experiência do Usuário**. Autopublicação, 2021.

---

## Histórico de Versões

## Histórico de Versões
| Versão | Descrição | Data | Autor(es) | Data de revisão | Revisor(es) |
| :---: | :--- | :---: | :---: | :---: | :---: |
| 1.0 | Criação do documento | 19/05/2026 | [Pedro Americo](https://github.com/dev-americo) | 19/05/2026 | [Breno Teixeira](https://github.com/BrenoLTeixeira)|
| 1.1 | inserção funcionalidade 2 | 19/05/2026 | [Breno Teixeira](https://github.com/BrenoLTeixeira) | 19/05/2026 | [Gabriel Diniz](https://github.com/GabrielDiniz12)|
| 1.2 | inserção funcionalidade 4 | 19/05/2026 | [Gabriel Diniz](https://github.com/GabrielDiniz12) | 19/05/2026 | [Julia Gabriella](https://github.com/juliagabriellafs)|
| 1.3 | inserção funcionalidade 4 | 19/05/2026 | [Julia Gabriella](https://github.com/juliagabriellafs) | 19/05/2026 | [Lucas Oliveira](https://github.com/dev-LucasDpaula) |
| 1.4 | inserção funcionalidade 5 | 19/05/2026 | [Lucas Oliveira](https://github.com/dev-LucasDpaula) | 19/05/2026 | [Pedro Ian](https://github.com/pedroiaan)|
| 1.5 | inserção funcionalidade 6 | 19/05/2026 | [Pedro Ian](https://github.com/pedroiaan) | 19/05/2026 | [Pedro Lucas](https://github.com/Pwdrinho) |
| 1.6 | inserção funcionalidade 3 | 19/05/2026 | [Pedro Lucas](https://github.com/Pwdrinho) | 19/05/2026 | [Pedro Americo](https://github.com/dev-americo) |
| 1.7 | inserção respostas das perguntas realizadas na entrevista 2| 22/05/2026 | [Gabriel Diniz](https://github.com/GabrielDiniz12) e [Pedro Lucas](https://github.com/Pwdrinho) | 22/05/2026 | [Julia Gabriella](https://github.com/juliagabriellafs)|
| 1.8 | Remoção das respostas das perguntas realizadas na entrevista 2| 01/07/2026 | [Gabriel Diniz](https://github.com/GabrielDiniz12) e [Pedro Lucas](https://github.com/Pwdrinho) | 01/07/2026 | [Lucas Oliveira](https://github.com/dev-LucasDpaula)|
| 1.9 | Adição da tabela de contribuição | 01/07/2026 | [Gabriel Diniz](https://github.com/GabrielDiniz12) | 01/07/2026 | [Pedro Lucas](https://github.com/Pwdrinho) |
