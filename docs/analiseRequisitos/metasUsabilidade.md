# Metas de Usabilidade e Qualidade de IHC
### Projeto de Reprojeto do Portal da Fundação Hemocentro de Brasília (FHB)

---

## 1. Introdução

As metas de usabilidade aqui apresentadas foram elaboradas diretamente da fase de **Análise de Requisitos** do ciclo de vida de Engenharia de Usabilidade proposto por **Mayhew (1999)**, integrando sistematicamente os artefatos produzidos nas etapas anteriores deste projeto. Especificamente, cada meta deriva da convergência entre quatro fontes de conhecimento: o **Perfil do Usuário**, a **Análise de Tarefas**, as **Características da Plataforma** e os **Princípios Gerais de Projeto**. Conforme descrito por Barbosa et al. (2021, p. 103) [[1]](#ref1), essa atividade

> "envolve definir os fatores de qualidade de uso que devem ser priorizados no projeto, como serão avaliados ao longo do processo de design, e quais faixas de valores são inaceitáveis, aceitáveis e ideais para cada indicador de interesse."

No presente projeto, optamos por um **método de inspeção** em detrimento de testes empíricos com usuários nesta fase inicial. Essa escolha se justifica pelo estágio atual do processo — ainda na transição do espaço do problema para o espaço da solução — e se fundamenta na premissa de que avaliações analíticas e heurísticas permitem identificar problemas de usabilidade de forma sistemática, por inspeção direta da interface por especialistas (Barbosa et al., 2021, Cap. 11 e 12) [[1]](#ref1).

Para cada funcionalidade proposta, os **indicadores de interesse** foram definidos como métricas inspecionáveis — grandezas objetivas e verificáveis pelos próprios designers na interface, sem necessidade de recrutamento de participantes —, tais como: número de redirecionamentos externos, quantidade de passos até a conclusão da tarefa, presença ou ausência de mecanismos de validação de campos, e número de documentos que requerem manipulação offline.

Seguindo a **regra de ouro da Engenharia de Usabilidade de Nielsen** [[2]](#ref2), cada indicador é avaliado em três faixas de valores, que funcionam como critérios de aceite do reprojeto:

<font id="tab1" size="3"><p class="table-source"><b>Tabela 1</b> - Legenda das faixas de valores de usabilidade</p></font>

| Faixa | Significado |
|---|---|
| 🔴 **Inaceitável** | Nível de usabilidade verificado no portal atual — o estado que justifica a intervenção. |
| 🟡 **Aceitável** | Nível mínimo de melhoria que a funcionalidade redesenhada deve obrigatoriamente atingir. |
| 🟢 **Ideal** | Nível máximo almejado, alcançável com a funcionalidade proposta e inspecionável na solução de design. |

O presente documento cobre as **funcionalidades** priorizadas para o reprojeto, cada qual com sua respectiva meta de usabilidade, justificativa de intervenção, indicador de inspeção e faixas de valores.

---

## 2. Funcionalidades e Metas de Usabilidade

---

### 2.1 Agendamento Interativo e Logístico para Grupos

**Caminho no portal atual:** Menu "Quero Doar" › "Tipos de Doação" › "Doação em Grupo"
**URL:** `https://www.fhb.df.gov.br/doacao-em-grupo` [[3]](#ref3)

---

#### Meta de Usabilidade (Aspecto de IHC): Simplicidade nas estruturas das tarefas

A funcionalidade deve **simplificar drasticamente a estrutura da tarefa** de organização de uma campanha de doação em grupo, eliminando a ruptura de canal que hoje força o organizador a migrar para telefone ou WhatsApp no meio do processo. Todas as etapas — do cadastro da campanha à confirmação do transporte — devem ser resolvidas em uma sequência guiada e coesa dentro do próprio portal, reduzindo a carga de planejamento externo exigida do usuário e as oportunidades de falha por omissão de informação.

---

#### Justificativa da Intervenção

**Cenário problemático atual:** O portal não dispõe de qualquer mecanismo interativo de agendamento para grupos. A página atual tem caráter exclusivamente informativo, listando as regras de elegibilidade (grupos de 10 a 15 pessoas com direito a transporte gratuito) e orientando o usuário a ligar para `(61) 3327-4413` ou enviar mensagem via WhatsApp para efetivar o agendamento [[3]](#ref3). Esse modelo impõe ao organizador uma **ruptura de canal** — o usuário precisa sair da interface digital e concluir a tarefa por telefone ou mensageiro —, o que gera dependência de horário de atendimento, risco de perda de informações e ausência de confirmação formal dentro do sistema.

**Solução idealizada:** Um assistente de agendamento nativo que guie o organizador por etapas: (1) cadastro da campanha e dos dados do grupo, (2) triagem de elegibilidade em tempo real, (3) escolha de data e horário com disponibilidade visível em calendário, e (4) confirmação de transporte (van), gerando um protocolo de confirmação ao final — tudo dentro do domínio `fhb.df.gov.br`, sem nenhuma saída para canais externos.

---

#### Indicador de IHC (Métrica de Inspeção)

> **Número de redirecionamentos externos ou trocas de canal obrigatórias para concluir o agendamento de grupo com transporte.**

Entende-se por "redirecionamento externo" qualquer instrução ou link que force o usuário a migrar para fora do portal (telefone, WhatsApp, e-mail, Google Forms, etc.) para dar prosseguimento ou concluir a tarefa.

---

#### Faixas de Valores

<font id="tab2" size="3"><p class="table-source"><b>Tabela 2</b> - Faixas de valores — Agendamento Interativo e Logístico para Grupos</p></font>

| Faixa | Valor | Descrição |
|---|---|---|
| 🔴 **Inaceitável** | ≥ 2 redirecionamentos externos | Situação atual: o usuário é instruído a sair do portal e usar telefone **e/ou** WhatsApp para agendar o grupo e confirmar o transporte. A tarefa não pode ser concluída integralmente na interface digital. |
| 🟡 **Aceitável** | 1 redirecionamento externo | O formulário de campanha é nativo, mas a confirmação da van ainda requer contato externo (ex.: uma ligação de retorno da FHB). A tarefa é majoritariamente digital, porém não totalmente autônoma. |
| 🟢 **Ideal** | 0 redirecionamentos externos | Agendamento completo — campanha, triagem, seleção de data/hora e confirmação de transporte — realizado integralmente dentro do portal, com emissão de protocolo digital ao final. Nenhuma instrução de saída para canal externo está presente na interface. |

---

### 2.2 Solicitação e Gestão Online de Dispensação Domiciliar

**Caminho no portal atual:** Menu "Coagulopatias" › "Atendimento Ambulatorial"
**URL:** `https://www.fhb.df.gov.br/ambulatorio` [[4]](#ref4)

---

#### Meta de Usabilidade (Aspecto de IHC): Promoção da eficiência do usuário

A funcionalidade deve **promover a eficiência do paciente crônico**, eliminando os deslocamentos físicos desnecessários para operações de natureza puramente administrativa. O painel digital deve permitir que o paciente envie relatórios e solicite reposição de medicamentos de forma assíncrona e autônoma — garantindo que o portal proteja o trabalho do usuário e não o faça aguardar ou deslocar-se à toa para tarefas que podem ser plenamente realizadas de forma remota.

---

#### Justificativa da Intervenção

**Cenário problemático atual:** A seção "Entrega Domiciliar de Medicamentos" do portal tem caráter puramente descritivo. Não há botão de solicitação, formulário de envio ou mecanismo algum de interação. A instrução explícita presente na página é: *"Para solicitar a inclusão no programa de entrega domiciliar, fale com o médico do ambulatório durante sua próxima consulta."* [[4]](#ref4) Isso implica que o paciente — muitas vezes com mobilidade comprometida por sua condição clínica — precisa aguardar uma consulta presencial para iniciar ou atualizar seu acesso ao programa, tornando o portal **funcionalmente inútil** para essa tarefa.

**Solução idealizada:** Um painel de controle integrado ao portal, acessível mediante login, onde o paciente pode: (1) enviar eletronicamente os relatórios periódicos de sangramentos e consumo de fator de coagulação (upload de arquivos), (2) solicitar reposição de estoque com histórico de pedidos visível, e (3) acompanhar o status da solicitação em tempo real, sem necessidade de qualquer deslocamento físico para tarefas administrativas rotineiras.

---

#### Indicador de IHC (Métrica de Inspeção)

> **Número de etapas que exigem presença física ou deslocamento do paciente para realizar uma solicitação ou atualização de relatório no programa de dispensação domiciliar.**

Entende-se por "etapa presencial obrigatória" qualquer passo do fluxo que só possa ser executado fisicamente no ambulatório (ex.: entrega de documento em mãos, assinatura presencial, consulta de rotina para comunicar informação administrativa).

---

#### Faixas de Valores

<font id="tab3" size="3"><p class="table-source"><b>Tabela 3</b> - Faixas de valores — Solicitação e Gestão Online de Dispensação Domiciliar</p></font>

| Faixa | Valor | Descrição |
|---|---|---|
| 🔴 **Inaceitável** | ≥ 1 etapa presencial obrigatória para solicitações de rotina | Situação atual: **todas** as solicitações e atualizações do programa exigem consulta física ao ambulatório. O portal não oferece nenhuma funcionalidade transacional para essa tarefa. |
| 🟡 **Aceitável** | 0 etapas presenciais para upload de relatórios; 1 etapa presencial apenas para inclusão inicial no programa | O painel digital permite envio de relatórios e pedidos de reposição online. A presença física é exigida somente na primeira inscrição no programa — situação justificável por protocolos clínicos. |
| 🟢 **Ideal** | 0 etapas presenciais para qualquer operação administrativa de rotina | O painel integrado cobre todo o ciclo administrativo do programa (upload de relatórios, solicitação de reposição, acompanhamento de status) sem nenhuma exigência de deslocamento físico. Consultas clínicas presenciais permanecem no escopo médico, não administrativo. |

---

### 2.3 Gestão Dinâmica de Formulários Clínicos e Hemovigilância

**Caminho no portal atual:** Menu "Hemorrede DF" › "Unidades Conveniadas" › "Reações e Hemovigilância"
**URL:** `https://www.fhb.df.gov.br/unidades-conveniadas` [[5]](#ref5)

---

#### Meta de Usabilidade (Aspecto de IHC): Projeto para erros

A funcionalidade deve **projetar ativamente para a prevenção de erros**: o sistema deve antecipar que campos críticos serão deixados em branco ou preenchidos incorretamente — especialmente em situações de urgência médica — e impedir a submissão de formulários clínicos incompletos ou inconsistentes. Em conformidade com o princípio, o design não pode depender exclusivamente da atenção do profissional de saúde para garantir a integridade do documento; a própria interface deve ser o mecanismo de defesa, com validação campo a campo em tempo real e bloqueio de submissão enquanto houver lacunas que possam comprometer o bloqueio de um lote de sangue.

---

#### Justificativa da Intervenção

**Cenário problemático atual:** Os formulários clínicos disponíveis no portal — incluindo os Anexos 4 (Formulário de Solicitação de Hemocomponentes) e Anexos 13 a 17 (formulários de hemovigilância, incluindo o FIRT) — são disponibilizados exclusivamente como arquivos PDF estáticos para download [[5]](#ref5). O profissional de saúde precisa baixar o arquivo, preencher manualmente (ou em PDF editável sem validação), e enviar por meios externos ao portal. Esse fluxo não realiza nenhuma verificação de campos obrigatórios, não previne inconsistências (ex.: lote de sangue sem número de série) e não dispara alertas em tempo real. Em um contexto de urgência transfusional, uma notificação incompleta pode atrasar o bloqueio sistêmico de um lote de sangue contaminado.

**Solução idealizada:** Formulários dinâmicos nativos no portal, com validação ativa campo a campo (ex.: alertas imediatos ao tentar avançar com campos obrigatórios vazios ou com formato inválido), bloqueio de submissão enquanto campos críticos estiverem incompletos, e disparo automatizado de alertas de bloqueio preventivo de lotes diretamente para o sistema da FHB ao final do preenchimento.

---

#### Indicador de IHC (Métrica de Inspeção)

> **Proporção de campos obrigatórios do formulário que possuem mecanismo de validação ativa com feedback imediato ao usuário (verificável por inspeção da interface).**

Entende-se por "validação ativa com feedback imediato" a presença, inspecionável no código ou protótipo da interface, de uma reação visual ou textual que ocorre no momento do preenchimento incorreto ou da tentativa de avanço com campo vazio — distinguindo-se de mensagens de erro genéricas exibidas somente após a submissão completa.

---

#### Faixas de Valores

<font id="tab4" size="3"><p class="table-source"><b>Tabela 4</b> - Faixas de valores — Gestão Dinâmica de Formulários Clínicos e Hemovigilância</p></font>

| Faixa | Valor | Descrição |
|---|---|---|
| 🔴 **Inaceitável** | 0% dos campos com validação ativa | Situação atual: formulários em PDF estático não possuem nenhuma validação de campo. O documento pode ser submetido incompleto ou com dados inconsistentes sem qualquer aviso ao profissional durante o preenchimento. |
| 🟡 **Aceitável** | ≥ 70% dos campos obrigatórios com validação ativa | O formulário dinâmico valida a maioria dos campos críticos em tempo real. Alguns campos menos críticos podem ainda carecer de validação específica, mas o núcleo do formulário — identificação do paciente, lote de sangue, tipo de reação — é plenamente validado. |
| 🟢 **Ideal** | 100% dos campos obrigatórios com validação ativa + bloqueio de submissão | Nenhum campo obrigatório pode ser ignorado. A submissão do formulário é bloqueada programaticamente enquanto houver inconsistências. Campos de lote de sangue possuem validação de formato específico (ex.: código alfanumérico padronizado), e o sistema dispara confirmação de recebimento e alerta de bloqueio ao sistema da FHB automaticamente. |

---

### 2.4 Fluxo Integrado de Emissão de Carteirinha e Laudo de Fenotipagem Sanguínea

**Caminho no portal atual:** Menu "Doença Falciforme" › "Para Pacientes" › "Carteirinha de Identificação do Paciente"
**URL:** `https://www.fhb.df.gov.br/para-pacientes` [[6]](#ref6)

---

#### Meta de Usabilidade (Aspecto de IHC): Correspondência com as expectativas dos usuários

A funcionalidade deve **corresponder às expectativas naturais do usuário**: ao acessar o portal institucional da FHB para solicitar a Carteirinha de Identificação e o Laudo de Fenotipagem Sanguínea, o usuário espera permanecer no mesmo ambiente digital e receber uma confirmação clara de que o sistema processará e enviará os documentos solicitados. O design deve honrar esse mapeamento mental, eliminando redirecionamentos para domínios externos e garantindo que o sistema forneça um feedback imediato e compreensível sobre o andamento da solicitação.

---

#### Justificativa da Intervenção

**Cenário problemático atual:** Ao clicar no link de solicitação da Carteirinha de Identificação da Doença Falciforme, o usuário é redirecionado para fora do portal da FHB, caindo em um formulário genérico do Google Forms (`forms.gle/ct4c7RF5LQejPbsV7`) [[6]](#ref6). Essa ruptura de domínio é problemática por duas razões principais: (1) o usuário perde a identidade visual e o contexto institucional da FHB, gerando desconfiança; e (2) o Google Forms não realiza nenhum cruzamento de dados clínicos do paciente para a geração do Laudo de Fenotipagem Sanguínea, tornando impossível a emissão integrada desse documento pela mesma interface.

**Solução idealizada:** Um formulário nativo no portal da FHB com um campo opcional no formato "Sim/Não" que permita ao paciente solicitar, no mesmo fluxo, a emissão do Laudo de Fenotipagem Sanguínea. Ao selecionar "Sim", o sistema deve exibir um feedback imediato e claro — visível na própria tela — informando que realizará a busca nos dados cadastrais e enviará o laudo para o e-mail cadastrado do paciente. O fluxo completo deve ocorrer integralmente dentro do portal, sem nenhuma saída para domínios externos.

---

#### Indicador de IHC (Métrica de Inspeção)

> **Número de redirecionamentos externos ocorridos durante o fluxo completo de solicitação da carteirinha e do laudo de fenotipagem**, combinado com a **presença inspecionável de um feedback imediato e claro confirmando o envio do laudo por e-mail**.

Este é um indicador composto: a dimensão de eficiência é medida pelos redirecionamentos externos; a dimensão de comunicabilidade é verificada pela existência de uma mensagem ou elemento visual — inspecionável na interface — que confirme ao usuário, de forma imediata, que o sistema processará a solicitação do laudo e enviará o documento para o e-mail cadastrado.

---

#### Faixas de Valores

<font id="tab5" size="3"><p class="table-source"><b>Tabela 5</b> - Faixas de valores — Fluxo Integrado de Emissão de Carteirinha e Laudo de Fenotipagem Sanguínea</p></font>

| Faixa | Valor | Descrição |
|---|---|---|
| 🔴 **Inaceitável** | ≥ 1 redirecionamento externo **e** ausência da opção de solicitar o laudo integrado | Situação atual: o usuário é redirecionado para o Google Forms (domínio externo) e não encontra nenhum mecanismo para solicitar o Laudo de Fenotipagem Sanguínea no mesmo fluxo. Dois problemas concomitantes: ruptura de canal e ausência de integração para emissão do laudo. |
| 🟡 **Aceitável** | 0 redirecionamentos externos **e** feedback do sistema sobre a emissão do laudo parcial ou genérico | Formulário nativo na FHB, sem saída para domínios externos. O campo opcional para solicitação do laudo está presente, porém o feedback exibido ao usuário após a seleção é genérico ou incompleto — não informando claramente o processamento e o envio por e-mail. |
| 🟢 **Ideal** | 0 redirecionamentos externos **e** campo opcional com feedback claro, imediato e visual informando o processamento e envio por e-mail | Formulário 100% nativo. O campo "Sim/Não" para solicitação do laudo está presente e, ao ser acionado, exibe imediatamente uma mensagem visual clara confirmando que o sistema realizará a busca nos dados cadastrais e enviará o Laudo de Fenotipagem Sanguínea para o e-mail cadastrado do paciente. O usuário não precisa de nenhuma ação adicional ou contato externo para concluir a solicitação. |

---

### 2.5 Agendamento Escolar / Institucional com Gestão em Lote

**Caminho no portal atual:** Menu "Educação" › "Visita Técnica" (HemoTour)
**URL:** `https://www.fhb.df.gov.br/visita-tecnica` [[7]](#ref7)

---

#### Meta de Usabilidade (Aspecto de IHC): Projeto para erros

A funcionalidade deve **projetar para a prevenção do erro de submissão incompleta**: o sistema deve assumir que o envio de autorizações parciais para turmas com menores de idade é um erro que certamente ocorrerá se a interface não interceptar ativamente. O mecanismo de verificação preventiva — que compara o número de documentos enviados com o número de alunos informado antes da confirmação final — é a salvaguarda central desta meta, complementada pela simplificação do processo de envio por meio de upload em lote que reduz as oportunidades de omissão.

---

#### Justificativa da Intervenção

**Cenário problemático atual:** O portal não oferece nenhum mecanismo interativo de agendamento escolar. A página do HemoTour limita-se a listar regras de vestimenta e número máximo de alunos (até 15 por turma), orientando o responsável a entrar em contato por telefone ou e-mail (`unitec@fhb.gov.br`) para agendar a visita [[7]](#ref7). Para turmas com menores de idade, o educador precisa anexar as autorizações dos responsáveis por cada aluno — um processo que, feito por e-mail convencional, não oferece nenhuma verificação de completude: o e-mail pode ser enviado com 8 de 15 autorizações e a ausência só será detectada manualmente pela equipe da FHB, potencialmente causando cancelamento de última hora.

**Solução idealizada:** Um portal de agendamento escolar com (1) interface de upload em lote, permitindo o envio de múltiplos arquivos de autorização em uma única operação; (2) verificação automatizada de completude — o sistema compara o número de autorizações enviadas com o número de alunos informados e emite alerta preventivo caso haja divergência, bloqueando ou sinalizando a submissão antes da confirmação; e (3) confirmação formal de agendamento com protocolo gerado ao final, tudo dentro do portal.

---

#### Indicador de IHC (Métrica de Inspeção)

> **Número de operações de upload individuais necessárias para enviar as autorizações de uma turma completa**, combinado com a **presença inspecionável de mecanismo de verificação preventiva de autorizações ausentes** antes da confirmação do agendamento.

Entende-se por "operação de upload individual" cada ação separada de seleção e envio de arquivo. O indicador composto avalia tanto a eficiência do processo (quantidade de interações para completar a tarefa) quanto a segurança no uso (existência de verificação preventiva de incompletude).

---

#### Faixas de Valores

<font id="tab6" size="3"><p class="table-source"><b>Tabela 6</b> - Faixas de valores — Agendamento Escolar / Institucional com Gestão em Lote</p></font>

| Faixa | Valor | Descrição |
|---|---|---|
| 🔴 **Inaceitável** | Nenhuma interface digital de upload disponível **e** ausência de qualquer verificação de completude | Situação atual: o envio de autorizações é feito por e-mail convencional, exigindo uma mensagem por arquivo ou uma mensagem com múltiplos anexos sem estrutura. Não há verificação de completude. A ausência de autorização de um aluno é detectada apenas manualmente pela equipe da FHB, sem alerta proativo ao educador. |
| 🟡 **Aceitável** | Upload nativo com múltiplos arquivos em uma única operação **e** aviso de incompletude **após** a submissão | O portal aceita upload em lote (seleção múltipla de arquivos em uma única interação). O sistema verifica e informa ao educador sobre autorizações ausentes, mas o faz apenas após o envio da solicitação — exigindo uma segunda submissão corretiva. |
| 🟢 **Ideal** | Upload em lote em operação única **e** verificação preventiva de completude **antes** da confirmação, com bloqueio ou alerta proativo | O sistema realiza a contagem de documentos enviados em relação ao número de alunos informado **em tempo real**, durante o preenchimento — alertando proativamente sobre autorizações faltantes e impedindo ou sinalizando claramente a submissão incompleta antes que a solicitação seja confirmada. Nenhum agendamento pode ser finalizado com documentação incompleta sem que o educador seja explicitamente avisado. |

---

### 2.6 Triagem e Redirecionamento Digital

**Caminho no portal atual:** Menu "Quero Doar" › "Antes de Doar" › "Sangria Terapêutica"
**URL:** `https://www.fhb.df.gov.br/sangria-terapeutica` [[8]](#ref8)

---

#### Meta de Usabilidade (Aspecto de IHC): Correspondência com as expectativas dos usuários e Projeto para erros

A funcionalidade deve **corrigir a contradição estrutural** entre a expectativa do paciente incompatível — que acessa o portal convicto de que pode agendar uma sangria terapêutica de rotina — e a realidade do serviço — que não atende esse tipo de demanda espontânea. O sistema não pode se limitar a textos informativos estáticos: deve antecipar ativamente o equívoco do usuário, conduzi-lo por uma triagem interativa de no máximo 3 passos que detecte a incompatibilidade clínica precocemente e emita um redirecionamento digital claro para a rede pública de saúde adequada (UBS ou hospital), impedindo o deslocamento físico em vão ao Hemocentro.

---

#### Justificativa da Intervenção

**Cenário problemático atual:** A página de Sangria Terapêutica está alocada dentro do menu "Quero Doar", o que induz o paciente leigo a acreditar que o Hemocentro presta esse serviço de rotina. A página contém exclusivamente texto estático informando que a demanda espontânea não é atendida [[8]](#ref8). O paciente — frequentemente idoso, com baixo letramento digital e desconhecimento dos jargões clínicos — não consegue processar essa informação de forma eficaz: cria a falsa expectativa de que há algum agendamento disponível, desloca-se fisicamente até a unidade e só então descobre a incompatibilidade. Esse cenário configura simultaneamente uma violação de **correspondência com as expectativas dos usuários** (a arquitetura de informação induz ao erro por posicionar o conteúdo dentro do menu de doação) e de **projeto para erros** (o sistema não realiza nenhuma defesa ativa contra o deslocamento indevido do paciente incompatível).

**Solução idealizada:** Um assistente de triagem interativa integrado à página, com no máximo 3 passos sequenciais: (1) identificação do tipo de serviço buscado pelo paciente (via seleção guiada, sem jargões técnicos); (2) verificação da compatibilidade clínica com base na resposta anterior; e (3) emissão automática de um redirecionamento digital claro — com nome, endereço e contato da unidade de saúde pública adequada — caso a incompatibilidade seja detectada. O assistente deve ser o primeiro elemento interativo visível da página, posicionado antes de qualquer bloco de texto estático, garantindo que o erro seja interceptado antes que o paciente tome qualquer decisão de deslocamento.

---

#### Indicador de IHC (Métrica de Inspeção)

> **Número de passos interativos exigidos para identificar a incompatibilidade clínica do paciente e fornecer um redirecionamento seguro para fora do sistema.**

Entende-se por "passo interativo" cada etapa de resposta ativa do usuário (ex.: seleção de opção, confirmação de escolha) que o assistente de triagem exige até a emissão do redirecionamento. O indicador mede tanto a existência do mecanismo interativo quanto a sua concisão — avaliando se a triagem é suficientemente rápida para interceptar o usuário antes que o deslocamento físico seja cognitivamente decidido.

---

#### Faixas de Valores

<font id="tab8" size="3"><p class="table-source"><b>Tabela 8</b> - Faixas de valores — Triagem e Redirecionamento Digital</p></font>

| Faixa | Valor | Descrição |
|---|---|---|
| 🔴 **Inaceitável** | 0 passos interativos (texto estático) | Situação atual: a página contém apenas texto corrido informando a ausência do serviço. O paciente incompatível não recebe nenhuma triagem ativa nem redirecionamento digital e, frequentemente, não interpreta corretamente o aviso — deslocando-se fisicamente ao Hemocentro em vão. |
| 🟡 **Aceitável** | Aviso em formato pop-up passivo, sem triagem ativa | A interface exibe um aviso destacado (modal ou banner de alerta) informando que o serviço não é prestado espontaneamente, com uma sugestão genérica de procurar a rede pública. Há um redirecionamento passivo, mas o sistema não realiza triagem individualizada nem emite encaminhamento específico para a unidade correta. |
| 🟢 **Ideal** | Triagem ativa em até 3 passos com emissão de redirecionamento claro | O assistente de triagem intercepta o paciente em no máximo 3 passos interativos, identifica a incompatibilidade clínica de forma individualizada e emite automaticamente um redirecionamento digital com informações precisas sobre a unidade de saúde pública adequada (UBS ou hospital). Nenhum paciente incompatível conclui a interação sem receber orientação clara de encaminhamento. |

---

## 3. Síntese Comparativa das Metas

A tabela a seguir consolida as seis metas de usabilidade definidas, permitindo uma visão panorâmica dos princípios gerais de projeto adotados, dos indicadores e das faixas de valores estabelecidas para o reprojeto do portal da FHB.

<font id="tab9" size="3"><p class="table-source"><b>Tabela 9</b> - Síntese comparativa das metas de usabilidade</p></font>

| # | Funcionalidade | Princípio Geral de Projeto | Indicador Principal | Inaceitável 🔴 | Aceitável 🟡 | Ideal 🟢 |
|---|---|---|---|---|---|---|
| 1 | Agendamento de Grupos | Simplicidade nas estruturas das tarefas | Redirecionamentos externos para concluir o agendamento | ≥ 2 | 1 | 0 |
| 2 | Dispensação Domiciliar | Promoção da eficiência do usuário | Etapas presenciais obrigatórias para operações de rotina | ≥ 1 | 0 (exceto inclusão inicial) | 0 (todas as operações administrativas) |
| 3 | Formulários Clínicos e Hemovigilância | Projeto para erros | % de campos obrigatórios com validação ativa | 0% | ≥ 70% | 100% + bloqueio de submissão |
| 4 | Emissão de Carteirinha e Laudo de Fenotipagem Sanguínea | Correspondência com as expectativas dos usuários | Redirecionamentos externos + presença inspecionável de feedback imediato e claro confirmando o envio do laudo por e-mail | ≥ 1 redirecionamento e ausência da opção de solicitar o laudo integrado | 0 redirecionamentos, mas feedback sobre emissão do laudo parcial ou genérico | 0 redirecionamentos e campo opcional com feedback claro, imediato e visual informando o processamento e envio por e-mail |
| 5 | Agendamento Escolar em Lote | Projeto para erros | Operações de upload individuais + verificação preventiva de completude | Sem interface digital e sem verificação | Upload em lote, verificação pós-envio | Upload em lote, verificação preventiva em tempo real |
| 6 | Triagem e Redirecionamento Digital | Correspondência com as expectativas dos usuários + Projeto para erros | Passos interativos para identificar incompatibilidade e emitir redirecionamento | 0 passos (texto estático) | Pop-up passivo, sem triagem ativa | Triagem ativa em ≤ 3 passos com redirecionamento claro |

---

## 4. Considerações Finais

As metas de usabilidade aqui definidas orientarão a fase subsequente do processo de Engenharia de Usabilidade: a elaboração de designs paralelos, a construção de protótipos e, eventualmente, os testes empíricos com representantes dos perfis de usuário identificados no projeto. Conforme Nielsen (1994) [[2]](#ref2) e Barbosa et al. (2021, p. 105) [[1]](#ref1), o design iterativo pressupõe que "a cada iteração de design e avaliação, alguns problemas são corrigidos, e o processo deve se repetir até que as metas de usabilidade tenham sido alcançadas." Portanto, os indicadores e faixas de valores aqui estabelecidos funcionarão como **critérios de aceite inspecionáveis** em cada ciclo de avaliação — garantindo que o reprojeto do portal da FHB seja conduzido com rigor metodológico e com foco mensurável na qualidade de uso das funcionalidades propostas.

---

## Bibliografia

<a id="ref1"></a>
> BARBOSA, Simone D. J.; SILVA, Bruno Santana da; SILVEIRA, Milene Selbach; GASPARINI, Isabela; DARIN, Ticianne; BARBOSA, Gabriel D. J. **Interação Humano-Computador e Experiência do Usuário.** Rio de Janeiro: Autopublicação, 2021.

<a id="ref2"></a>
> NIELSEN, Jakob. **Usability Engineering.** San Francisco: Morgan Kaufmann, 1994.

<a id="ref3"></a>
> FUNDAÇÃO HEMOCENTRO DE BRASÍLIA (FHB). **Doação em Grupo**. Brasília, DF. Disponível em: <https://www.fhb.df.gov.br/doacao-em-grupo/>. Acesso em: 03 mai. 2026.

<a id="ref4"></a>
> FUNDAÇÃO HEMOCENTRO DE BRASÍLIA (FHB). **Atendimento Ambulatorial**. Brasília, DF. Disponível em: <https://www.fhb.df.gov.br/ambulatorio/>. Acesso em: 03 mai. 2026.

<a id="ref5"></a>
> FUNDAÇÃO HEMOCENTRO DE BRASÍLIA (FHB). **Unidades Conveniadas**. Brasília, DF. Disponível em: <https://www.fhb.df.gov.br/unidades-conveniadas/>. Acesso em: 03 mai. 2026.

<a id="ref6"></a>
> FUNDAÇÃO HEMOCENTRO DE BRASÍLIA (FHB). **Para Pacientes**. Brasília, DF. Disponível em: <https://www.fhb.df.gov.br/para-pacientes/>. Acesso em: 03 mai. 2026.

<a id="ref7"></a>
> FUNDAÇÃO HEMOCENTRO DE BRASÍLIA (FHB). **Visita Técnica (HemoTour)**. Brasília, DF. Disponível em: <https://www.fhb.df.gov.br/visita-tecnica/>. Acesso em: 03 mai. 2026.

<a id="ref8"></a>
> FUNDAÇÃO HEMOCENTRO DE BRASÍLIA (FHB). **Sangria Terapêutica**. Brasília, DF. Disponível em: <https://www.fhb.df.gov.br/sangria-terapeutica/>. Acesso em: 03 mai. 2026.

---

## Histórico de Versões

| Versão | Descrição | Data | Autor(es) | Data de revisão | Revisor(es) |
| ------ | ------ | ------ | ------ | ------ | ------ |
| 1.0 | Criação de Metas de Usabilidade | 03/05/2026 | [Julia Gabriella](https://github.com/juliagabriellafs) | 03/05/2026 | [Pedro Américo](https://github.com/dev-americo) |
| 2.0 | Atualização de Metas de Usabilidade | 09/05/2026 | [Lucas Oliveira](https://github.com/dev-LucasDpaula) | 11/05/2026 | [Julia Gabriella](https://github.com/juliagabriellafs) |
| 3.0 | Correção e atualização de Metas de Usabilidade | 22/05/2026 | [Julia Gabriella](https://github.com/juliagabriellafs) | 22/05/2026 | [Pedro Américo](https://github.com/dev-americo) |
| 4.0 | Revisão e correções de Metas de Usabilidade | 23/06/2026 | [Julia Gabriella](https://github.com/juliagabriellafs) | 23/06/2026 | [Pedro Américo](https://github.com/dev-americo) |