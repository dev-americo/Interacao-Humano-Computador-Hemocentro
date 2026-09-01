# Análise Documental: Manual para Unidades Conveniadas (Profissionais de Saúde)

---

## Introdução

O desenvolvimento de sistemas interativos responsáveis exige, antes de qualquer decisão de design, a compreensão do ambiente legal, normativo e operacional em que o sistema será inserido. Conforme **Barbosa et al. (2021)**, a documentação de processos e normas é insumo essencial da fase de análise em IHC, pois define restrições sobre o que o usuário poderá ou não fazer através do sistema — limites que não são negociáveis, independentemente de preferências de usuário ou conveniências técnicas.

Para fundamentar a análise de IHC e a criação de novas funcionalidades do portal da Fundação Hemocentro de Brasília (FHB) voltadas ao público profissional externo, foi analisado o seu **Manual para Unidades Conveniadas (Versão 2, MA Dihemo 01)**. O objetivo desta análise é mapear as responsabilidades e os fluxos de tarefas complexas que os profissionais de saúde precisam realizar no sistema para garantir a segurança e a rastreabilidade transfusional.

---

## A Análise Documental em IHC

Em IHC, a fase de análise precede qualquer decisão de design: é nela que se compreende quem são os usuários, quais tarefas realizam e em que contexto operam. Documentos normativos operacionais, como este manual, são fontes primárias valiosas, pois revelam o domínio do sistema, o vocabulário técnico, as responsabilidades de cada papel e os fluxos de tarefas que a interface digital precisa suportar de forma otimizada. 

Inserindo-se no ciclo de Engenharia de Usabilidade de Mayhew, o Manual para Unidades Conveniadas funciona como uma base de especificação de requisitos. Ele garante que o design do sistema previna erros de alta gravidade — como preenchimentos inadequados de dados clínicos ou falhas de comunicação — e esteja perfeitamente alinhado ao modelo mental e às tarefas reais das Unidades Conveniadas (UC).

---

## Mapeamento do Perfil e das Características do Usuário

A leitura do manual permitiu traçar o perfil dos profissionais de saúde que utilizam o sistema da FHB:

* **Identidade e Papel:** Profissionais de saúde externos vinculados aos hospitais e serviços de saúde que possuem convênio com a FHB. Os principais atores são o **Médico Responsável Técnico da Agência Transfusional (AT)**, **médicos plantonistas solicitantes** e os **funcionários da AT** (enfermeiros, biomédicos e técnicos).
* **Ambiente de Trabalho e Contexto de Uso:** Agências transfusionais e hospitais conveniados. O ambiente de trabalho pode ser caótico e de alta criticidade (como prontos-socorros, UTIs e centros cirúrgicos), onde os profissionais trabalham sob forte pressão de tempo.
* **Habilidades e Nível de Instrução:** Usuários com alto grau de instrução, mas letramento variado em sistemas computacionais. Utilizam jargões e termos técnicos da hematologia e hemoterapia diariamente (como *fenotipagem*, *aloimunização*, *Notivisa*, *SistHemo*).
* **Gravidade dos Erros:** **Altíssima**. Erros no preenchimento de dados do paciente ou na identificação de amostras e bolsas de sangue têm consequências graves, comprometendo a segurança do receptor.

---

## Entendimento das Restrições e Hierarquia de Tarefas

O Manual estabelece claramente como cada fluxo de trabalho deve ser executado e registrado. Do ponto de vista de IHC, essas definições se traduzem diretamente em regras de negócio e restrições de interface:

### 1. Diferenciação Crítica de Fluxos de Pedidos de Hemocomponentes
* **Solicitação de Rotina (Estoque):** É uma tarefa programada. O sistema deve permitir solicitações de reposição de estoque até as 12 horas do dia útil anterior à entrega. O pedido deve ser feito estritamente em "unidades" e nunca em "volume (ml)".
* **Solicitação de Emergência (Fora de Rotina):** É uma tarefa de altíssima prioridade, realizada por paciente em regime 24/7. A interface não pode exigir campos excessivos ou criar barreiras que atrasem a solicitação imediata. Em casos de inoperância do sistema (SistHemo), os processos manuais atuam como contingência.

### 2. Validação de Dados e Rastreabilidade Compulsória
O sistema deve ser projetado para garantir a **rastreabilidade total** das bolsas de sangue e dos receptores. A interface do módulo de Agência Transfusional da FHB deve cruzar dados em tempo real e obrigar o preenchimento de itens críticos, impedindo o envio de formulários incompletos:
* A Requisição de Transfusão (RT) deve conter obrigatoriamente: nome completo do paciente (sem abreviaturas), data de nascimento, sexo, diagnóstico e peso.
* As solicitações de hemocomponentes específicos (como hemácias fenotipadas) exigem a seleção de critérios precisos (escalas de imunogenicidade e diagnóstico do paciente).

### 3. Comunicação de Eventos Adversos e Hemovigilância
Em situações de reação transfusional (como suspeitas de TRALI ou contaminação bacteriana), a interface do sistema precisa agir como um canal de alerta imediato. O sistema deve permitir que o profissional registre a ocorrência rapidamente e instrua sobre a retirada e o descarte/recolhimento das bolsas envolvidas no estoque da AT, reduzindo a carga cognitiva do profissional em um momento de estresse no plantão.

---

## Conclusão da Análise

A análise documental do Manual para Unidades Conveniadas revela que o usuário das agências transfusionais atua em um contexto que exige precisão técnica absoluta e rapidez nas decisões. Ao contrário do doador comum, que prioriza o acolhimento visual e a facilidade de navegação, o foco do design para o profissional de saúde deve ser a **eficiência e a prevenção de erros**. 

Portanto, a interface do módulo de Unidades Conveniadas deve eliminar distrações estéticas desnecessárias, fornecer feedback em tempo real para minimizar erros de digitação e garantir que tarefas complexas (como o preenchimento de formulários de hemovigilância e controle de estoque) sejam simplificadas e totalmente digitalizadas.

---

## Referências Bibliográficas

> <a id="ref1"></a> [1] BARBOSA, Simone Diniz Junqueira et al. **Interação Humano-Computador e Experiência do Usuário.** 1. ed. Rio de Janeiro: Simone Diniz Junqueira Barbosa, 2021. E-book.

> <a id="ref2"></a> [2] FUNDAÇÃO HEMOCENTRO DE BRASÍLIA. **Manual para Unidades Conveniadas.** MA Dihemo 01, Versão 2. Brasília, DF: FHB, 2024-2027.

---

| Versão | Descrição | Data | Autor(es) | Data de revisão | Revisor(es) |
| ------ | ------ | ------ | ------ | ------ | ------ |
| 1.0 | Criação do documento de Análise Documental (Unidades Conveniadas) | 02/05/2026 | [Breno Teixeira](https://github.com/BrenoLTeixeira) | 03/05/2026 | [Gabriel Diniz](https://github.com/GabrielDiniz12) |