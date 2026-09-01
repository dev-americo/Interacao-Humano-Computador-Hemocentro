# Análise Documental: Estatuto da Fundação Hemocentro de Brasília
**Restrições Legais e Implicações para o Design de Sistemas Interativos**

---

## Introdução

O desenvolvimento de sistemas interativos responsáveis exige, antes de qualquer decisão de design, a compreensão do ambiente legal e normativo em que o sistema será inserido. Conforme [Barbosa et al. (2021)¹](#ref1), a documentação de processos e normas é insumo essencial da fase de análise em IHC, pois define restrições sobre o que o usuário poderá ou não fazer através do sistema — limites que não são negociáveis, independentemente de preferências de usuário ou conveniências técnicas.

O presente trabalho analisa o Estatuto da Fundação Hemocentro de Brasília (FHB), aprovado pelo [Decreto nº 44.407/2023³](#ref3). A FHB é uma fundação pública de direito público vinculada à Secretaria de Estado de Saúde do Distrito Federal, responsável pelo Sistema de Sangue, Componentes e Hemoderivados (SSCH). O objetivo é identificar as restrições legais inflexíveis que devem orientar o projeto de qualquer sistema interativo no contexto da FHB — ou seja, o que o sistema não pode fazer ou permitir por força de lei.

---

## A Análise Documental em IHC

Em IHC, a fase de análise precede qualquer decisão de design: é nela que se compreende quem são os usuários, quais tarefas realizam e em que contexto operam. Dentre as fontes de dados dessa fase, documentos normativos e institucionais ocupam posição especial, pois delimitam o espaço de soluções juridicamente válidas. [Barbosa et al. (2021)¹](#ref1) são diretos ao afirmar que a documentação de processos e normas define restrições sobre o que o usuário poderá ou não fazer através do sistema, e às vezes até como ele poderá utilizá-lo. Inserindo-se no [ciclo de Engenharia de Usabilidade de Mayhew (1999, apud BARBOSA et al., 2021¹)](#ref1), o Estatuto da FHB é, portanto, uma fonte primária de requisitos: informa quem são os atores do sistema, quais processos devem ser suportados e, sobretudo, quais ações são proibidas por lei.

---

## O Estatuto da Fundação Hemocentro de Brasília

O Estatuto da FHB, aprovado pelo [Decreto nº 44.407/2023³](#ref3), é um texto normativo constitutivo: rege a existência jurídica, a finalidade e o funcionamento da fundação, possuindo força de lei no Distrito Federal e vinculando, de modo absoluto, todos os atores — inclusive sistemas computacionais.

### Natureza Jurídica, Vinculação e Finalidade

O Art. 1º do Estatuto define a FHB como fundação pública de direito público, órgão do SUS vinculado à Secretaria de Estado de Saúde do DF. Essa natureza jurídica impõe aos sistemas interativos sujeição plena aos princípios da Administração Pública — legalidade, impessoalidade, moralidade, publicidade e eficiência — com exigências obrigatórias de transparência, controle e responsabilidade.

O Art. 2º estabelece o caráter científico-tecnológico, educacional e assistencial da FHB, sem fins lucrativos. Para o design, isso afasta qualquer lógica de persuasão comercial ou monetização, impondo uma orientação de serviço público comprometida com a saúde coletiva.

O Art. 3º posiciona a FHB como órgão gestor do SSCH, em harmonia com a [Lei nº 10.205/2001²](#ref2). Essa responsabilidade sistêmica exige que qualquer sistema interativo opere em múltiplos níveis organizacionais, atendendo usuários internos e externos.

### Os Princípios Orientadores como Restrições de Design

O Art. 4º enumera os princípios estruturantes da FHB que, na perspectiva de IHC, equivalem a metas de design com força normativa — seu descumprimento não é falha de qualidade, mas violação legal:

- Utilização exclusiva da doação voluntária e não remunerada do sangue (inciso I);
- Vedação da comercialização da coleta, processamento, estocagem, distribuição e transfusão do sangue, componentes e hemoderivados (inciso II);
- Proteção da saúde do doador, do receptor e do paciente (inciso III);
- Respeito ao direito do usuário sobre o conhecimento da origem do sangue transfundido (inciso IV);
- Difusão dos princípios e técnicas para o uso racional dos hemocomponentes e hemoderivados (inciso V);
- Primazia da atenção humanizada aos usuários e à ética no serviço público (inciso VI);
- Manutenção permanente e continuada do desenvolvimento de pessoas, de pesquisa e inovação tecnológica (inciso VII).

Na terminologia de [Barbosa et al. (2021)¹](#ref1), esses princípios constituem restrições de design — condicionantes que delimitam o espaço de soluções antes de qualquer decisão criativa. Um sistema que, ainda que inadvertidamente, permitisse intermediação comercial de hemocomponentes ou omitisse a origem do sangue transfundido violaria simultaneamente o Estatuto e os valores éticos fundamentais da IHC.

### As Competências Institucionais como Escopo Funcional do Sistema

O Art. 5º elenca 33 competências da FHB — da captação de doadores à manutenção de laboratórios de referência. Para a IHC, esse artigo constitui a base da análise de tarefas [(Barbosa et al., 2021¹)](#ref1): delineia o universo de ações que os sistemas devem suportar.

A pluralidade de competências revela stakeholders heterogêneos — doadores, pacientes com coagulopatias, profissionais de saúde, gestores, técnicos de laboratório —, cada um com objetivos e necessidades distintos. Essa diversidade obriga o designer a projetar sistemas flexíveis o suficiente para acolher perfis variados, sem jamais comprometer os princípios do Art. 4º.

Destaque especial cabe ao inciso XXIII, que impõe Hemovigilância, Retrovigilância e rastreabilidade plena dos registros hemoterápicos. Trata-se de requisito funcional com implicações diretas sobre o design: o sistema deve registrar e exibir informações de modo auditável, completo e temporalmente preciso, com exigências específicas sobre arquitetura da informação e fluxos de interação.

### Estrutura Organizacional e o Contexto de Uso

O Título III descreve a estrutura organizacional da FHB — Presidência, Conselhos, Colegiado de Gestão, Diretorias e Gerências. Para a IHC, essa estrutura delimita o contexto de uso [(Barbosa et al., 2021)¹](#ref1): as camadas hierárquicas informam quem são os usuários, quais são suas atribuições e como interagem com os sistemas.

A hierarquia estatutária implica diretamente a necessidade de diferentes níveis de acesso e permissão no sistema. Um servidor da GDIS tem atribuições e objetivos distintos dos de um membro do Conselho Fiscal; um sistema que ignore essa diferenciação viola tanto os princípios de segurança de IHC quanto as disposições estatutárias de competência.

Os Arts. 10 a 19 formalizam os processos decisórios do Conselho Deliberativo e do Colegiado de Gestão — aprovação de orçamentos, apreciação de contas, propostas de política. Na linguagem de IHC, essas são tarefas críticas que o sistema deve suportar com máximo cuidado, priorizando precisão, rastreabilidade e integridade dos dados.

---

## Restrições Legais Inflexíveis: O que o sistema NÂO pode fazer

Ao contrário das restrições de usabilidade — compromissos de qualidade negociáveis —, as restrições legais identificadas no Estatuto são limites intransponíveis: sua violação acarreta consequências jurídicas e compromete a legitimidade da organização. A seguir, analisam-se as principais.

### Proibição Absoluta de Qualquer Forma de Comercialização

O inciso II do Art. 4º, em consonância com a [Lei nº 10.205/2001²](#ref2), veda de forma expressa e absoluta a comercialização da coleta, processamento, estocagem, distribuição e transfusão de sangue e hemocomponentes — decorrência do princípio ético de que o sangue humano não pode ser mercadoria.

Em termos de design, isso impõe uma exigência de design negativo ativo: campos de valores monetários associados a doações, recompensas financeiras por doação ou cobranças não autorizadas por hemocomponentes a hospitais conveniados configuram violação estatutária. A ausência dessas funcionalidades deve ser planejada, não meramente acidental.

### Exclusividade da Doação Voluntária e Não Remunerada

O inciso I do Art. 4º restringe a captação à doação exclusivamente voluntária e não remunerada. Articulado com os incisos I e II do Art. 5º — que determinam a promoção da conscientização e a instituição de mecanismos de fidelização de doadores —, esse princípio é também uma diretriz de design positiva.

Portais de agendamento e aplicativos de captação devem comunicar com clareza o caráter voluntário e altruístico da doação. Segundo o critério de comunicabilidade de [Barbosa et al. (2021)¹](#ref1), a interface deve transmitir ao usuário que o ato de doação não envolve qualquer contrapartida financeira, preservando a integridade do princípio legal e a confiança do doador.

### Direito à Informação sobre a Origem do Sangue Transfundido

O inciso IV do Art. 4º garante ao paciente o direito de conhecer a origem do sangue transfundido. Qualquer sistema que gerencie transfusões deve preservar e disponibilizar, de forma segura e acessível, o registro de procedência de cada hemocomponente utilizado.

Na perspectiva de IHC, esse direito articula-se ao critério de acessibilidade da informação [(Barbosa et al., 2021)¹](#ref1). Um sistema que omita ou dificulte esse acesso — por falhas na arquitetura da informação ou por ausência de funcionalidades específicas — incorre simultaneamente em falha de qualidade de uso e violação dos direitos do paciente.

### Atenção Humanizada e Ética no Serviço Público

O inciso VI do Art. 4º consagra a primazia da atenção humanizada, que em IHC corresponde ao conceito de experiência do usuário (UX): mais do que eficiência funcional, envolve fatores emocionais, afetivos e éticos. [Barbosa et al. (2021)¹](#ref1) ressaltam que sistemas interativos devem contribuir positivamente para o bem-estar emocional dos usuários.

No contexto da FHB, os usuários frequentemente estão em situação de vulnerabilidade — doadores ansiosos diante da triagem, pacientes crônicos dependentes de hemostáticos. O Estatuto obriga o designer a projetar interfaces que reconheçam essa vulnerabilidade e respondam com empatia, clareza e suporte adequado.

### Respeito às Normas de Licitação e Contratos

O Art. 36 determina que contratações em geral sejam realizadas mediante processo licitatório público. Para sistemas de gestão administrativa, isso configura uma restrição de fluxo de trabalho inegociável: nenhuma funcionalidade pode contornar os rituais formais de contratação. Fluxos de aprovação, registros de justificativa e rastreabilidade de decisões administrativas não são opções de design — são obrigações legais.

---

## Implicações para o Design de Sistemas Intarativos da FHB

A análise realizada ao longo deste trabalho permite articular, de forma objetiva, as principais implicações do Estatuto da FHB para o design de sistemas interativos em IHC. Em síntese, o Estatuto estabelece:

- O sistema não pode implementar, direta ou indiretamente, qualquer mecanismo de compra, venda ou compensação financeira relacionada a sangue ou hemocomponentes;
- O sistema não pode omitir ou dificultar o acesso do paciente à informação sobre a origem do sangue transfundido;
- O sistema não pode permitir que o processo de doação de sangue seja associado, de qualquer forma, a recompensas financeiras ou transações comerciais;
- O sistema não pode subverter os fluxos formais de tomada de decisão previstos nos órgãos deliberativos da FHB (Conselho Deliberativo e Colegiado de Gestão);
- O sistema não pode contornar os requisitos de licitação pública estabelecidos para contratações administrativas;
- O sistema deve incorporar uma postura de cuidado e humanização, reconhecendo a vulnerabilidade dos usuários e respeitando a dimensão ética inerente ao contexto de saúde pública.

Essas restrições não são limites negativos que empobrecem o design. Ao contrário, elas conferem ao processo de design um sentido de responsabilidade e de comprometimento com valores que transcendem a mera funcionalidade técnica. Como afirmam [Barbosa et al. (2021)¹](#ref1), o design de IHC é um processo que deve articular os interesses dos stakeholders com os conhecimentos sobre intervenções avaliadas em casos semelhantes e com as possibilidades e limitações das tecnologias disponíveis. O Estatuto é, portanto, parte inalienável desse conhecimento contextual e sua análise rigorosa é condição para qualquer design que pretenda ser, ao mesmo tempo, útil, usável e legítimo.

---

## Conclusão

A análise do Estatuto da FHB demonstra que documentos normativos não são acessórios burocráticos: são mapas do território legal em que o sistema será implantado. As restrições identificada (proibição de comercialização, exclusividade da doação voluntária, direito à informação do paciente, atenção humanizada e obrigatoriedade de licitação) não são opções de design. São condicionantes inalienáveis que devem estar presentes desde a concepção dos requisitos até a avaliação final do sistema. Como afirmam [Barbosa et al. (2021)¹](#ref1), o design de IHC deve articular os interesses dos stakeholders com o conhecimento do contexto real de uso — e o Estatuto é parte indissociável desse conhecimento. Lê-lo com rigor é, em sentido pleno, um ato de design.

---

## Referências Bibliográficas

<a id="ref1"></a>
> BARBOSA, Simone D. J.; SILVA, Bruno Santana da; SILVEIRA, Milene Selbach; GASPARINI, Isabela; DARIN, Ticianne; BARBOSA, Gabriel D. J. **Interação Humano-Computador e Experiência do Usuário.** Rio de Janeiro: Autopublicação, 2021.

<a id="ref2"></a>
> BRASIL. **Lei nº 10.205, de 21 de março de 2001.** Regulamenta o § 4º do art. 199 da Constituição Federal, relativo à coleta, processamento, estocagem, distribuição e aplicação do sangue, seus componentes e derivados, estabelece o ordenamento institucional indispensável à execução adequada dessas atividades, e dá outras providências. Brasília, DF: Presidência da República, 2001.

<a id="ref3"></a>
> DISTRITO FEDERAL. **Decreto nº 44.407, de 04 de abril de 2023.** Aprova o Estatuto da Fundação Hemocentro de Brasília. Diário Oficial do Distrito Federal, Brasília, DF, 04 abr. 2023. Disponível em: https://www.fhb.df.gov.br/estatuto/. Acesso em: 01 mai. 2026.

## Histórico de Versões

| Versão | Descrição | Data | Autor(es) | Data de revisão | Revisor(es) |
| ------ | ------ | ------ | ------ | ------ | ------ |
| 1.0 | Criação do documento | 01/05/2026 | [Julia Gabriella](https://github.com/juliagabriellafs) | 02/05/2026 | [Lucas Oliveira](https://github.com/dev-LucasDpaula) |