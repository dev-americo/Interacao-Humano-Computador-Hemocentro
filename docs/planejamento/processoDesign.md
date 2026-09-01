## 1. Introdução

Antes de explorarmos a metodologia que guiará a análise e o aprimoramento do site do Hemocentro, é fundamental definir o conceito de design no contexto da Interação Humano-Computador (IHC). Desde a sua concepção, o projeto de um sistema interativo é compreendido como um processo iterativo que tem como propósito principal apoiar os usuários para que alcancem seus objetivos de forma eficaz.

De maneira geral, a atividade de design pode ser caracterizada por três etapas básicas e interdependentes:

- **Análise da situação atual:** envolve estudar e interpretar o contexto atual para identificar problemas.
- **Síntese de uma intervenção:** consiste em planejar e construir uma solução para atuar sobre o problema.
- **Avaliação da nova situação:** verifica os efeitos práticos da intervenção realizada na realidade analisada.

Para que essas três atividades sejam aplicadas de forma sistemática e rigorosa, recorre-se aos processos de design em IHC. Tais processos organizam como as etapas devem ser executadas e iteradas, garantindo que o desenvolvimento seja centrado nas necessidades dos usuários e que a equipe possa realizar refinamentos sucessivos tanto na compreensão do problema quanto na solução concebida.

O site do Hemocentro constitui o artefato deste estudo, no qual otimizações em interfaces e fluxos, como agendamento e requisitos de doação impactam diretamente a rotina de doadores e da instituição. Portanto, para garantir que essa intervenção gere consequências positivas e ofereça uma experiência de uso com alta qualidade, é indispensável a adoção de um modelo de processo de design estruturado, o qual será detalhado nas seções seguintes.

---

## 2. Modelo de processos de design

Para sistematizar as atividades básicas do design, a literatura de Interação Humano-Computador (IHC) propõe diversos modelos de processos que visam garantir a **qualidade do uso**. Cada modelo organiza como essas atividades devem ser executadas de forma iterativa, detalhando os artefatos consumidos e produzidos em cada uma delas. Entre as abordagens consagradas na área, destacam-se:

### 2.1 Ciclo de Vida Simples

Proposto por Preece, Sharp e Rogers, é um modelo direto e iterativo focado no design centrado no usuário. Ele segmenta a atividade de síntese em duas frentes: o (re)design conceitual e a construção de versões interativas, garantindo que propostas de solução sejam rapidamente avaliadas para guiar refinamentos sucessivos.

### 2.2 Ciclo de Vida em Estrela

Desenvolvido por Hix e Hartson (1993), organiza o processo em seis atividades interligadas. Seu principal diferencial é a não linearidade: a atividade de "avaliação" ocupa o centro do modelo (a "estrela"), exigindo que o resultado de qualquer etapa concluída passe obrigatoriamente por uma avaliação antes do avanço para a próxima fase.

### 2.3 Engenharia de Usabilidade de Nielsen

Proposto por Jakob Nielsen (1994), define um ciclo de vida baseado em dez atividades práticas para garantir a qualidade de uso. O modelo dá forte ênfase aos estágios iniciais do projeto (como conhecer o usuário e definir metas), baseando-se intensamente na construção de protótipos, design participativo e na execução de testes empíricos.

### 2.4 Engenharia de Usabilidade de Mayhew

Proposto por Deborah Mayhew (1999) <a href="#figura1">Figura 1</a>, este ciclo de vida possui uma visão holística e estruturada, organizando as diversas atividades de IHC em três fases principais para orientar de forma rigorosa a concepção de uma boa solução interativa:

<div align="center">
  <p class="table-source"><strong>Figura 1 - Atividades do Modelo de Ciclo de Vida de Mayhew</strong></p>
  
  <img src="../../assets/images/entrega1/ciclo-mayhew.png" alt="Descrição" id="figura1">

  <p class="table-source">Fonte: <a href="#ref1">BARBOSA e SILVA, 2011, p.106.¹</a> (2011).</p>
</div>

#### Análise de requisitos

Define as metas de usabilidade com base no perfil dos usuários, na análise de tarefas, nas possibilidades e limitações da plataforma, e em princípios gerais de projeto. Essas metas são formalizadas através de guias de estilo.

#### Design, Avaliação e Desenvolvimento

Divide a concepção da solução em três níveis iterativos de detalhamento:

- **Nível 1:** Reengenharia do trabalho e prototipação do modelo conceitual em baixa fidelidade;
- **Nível 2:** Definição de padrões de design de tela com protótipos de média fidelidade;
- **Nível 3:** Projeto detalhado da interface em alta fidelidade para implementação. Em todos os níveis, exige-se a avaliação iterativa.

#### Instalação

Coleta o feedback e as opiniões dos usuários após um período de uso real, servindo como base metodológica para melhorias contínuas ou desenvolvimento de novos sistemas.

---

Esta síntese articula os modelos de design em IHC e sua aplicabilidade prática segundo Barbosa e Silva (Cap. 6), oferecendo subsídios para os desafios do design centrado no usuário.

> **Referência:** BARBOSA, Simone Diniz Junqueira et al. *Interação Humano-Computador e Experiência do Usuário*. 1. ed. Rio de Janeiro: Autopublicação, 2021. Cap 6.

---

## 3. Justificativa da escolha do modelo para o Hemocentro

Visto que o site do Hemocentro constitui um artefato já em operação e que o objetivo central deste estudo reside na **otimização da experiência do usuário**, a **Engenharia de Usabilidade de Mayhew** foi selecionada como a metodologia norteadora.

Mayhew foi a metodologia escolhida para guiar a análise e o aprimoramento do site do Hemocentro devido à sua abordagem estruturada e ao alto nível de detalhamento de suas fases, características que reduzem a subjetividade no processo de design. Tratando-se de um sistema voltado para a saúde pública, onde falhas de comunicação ou fluxos de interface confusos podem desmotivar doadores, a adoção de um roteiro seguro e iterativo é indispensável.

Além disso, por se tratar de uma plataforma que já está em produção, o modelo de Mayhew permite uma aplicação prática estratégica. O processo de avaliação pode ser iniciado a partir da perspectiva da fase de **Instalação**, que consiste em analisar o feedback e as opiniões dos usuários diante da experiência de uso do sistema atual. A partir do diagnóstico desses dados reais para identificar pontos de melhoria, o processo retrocede para a fase de **Análise de Requisitos**. Essa dinâmica viabiliza a estruturação de mudanças mais assertivas que passarão por um **ciclo iterativo**, com avaliações diversas como formativas e somativas de refinamento e validação ao longo dos níveis de prototipação, assegurando que o aprimoramento das interfaces atenda de fato às necessidades dos doadores.

## 4. Referências Bibliográficas
<a id="ref1"></a>
>  [1] BARBOSA, Simone Diniz Junqueira et al. *Interação Humano-Computador e Experiência do Usuário*. 1. ed. Rio de Janeiro: Autopublicação, 2021.

---

## Histórico de versões

| Versão | Descrição | Data | Autor(es) | Data de revisão | Revisor(es) |
| :---: | :--- | :---: | :---: | :---: | :---: |
| 1.0 | Criação da página de design e inserção do conteúdo | 10/04/2026 | [Julia Gabriella](https://github.com/juliagabriellafs) e [Lucas Oliveira](https://github.com/dev-LucasDpaula)| 10/04/2026 | [Pedro Ian](https://github.com/pedroiaan)|
| 1.1 | Revisão após inspeção da entrega 1 | 11/04/2026 | [Julia Gabriella](https://github.com/juliagabriellafs) e [Lucas Oliveira](https://github.com/dev-LucasDpaula)| 11/04/2026 | [Pedro Ian](https://github.com/pedroiaan)|