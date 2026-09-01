## Características Gerais da Plataforma

De acordo com Barbosa et al. (2021), a definição das características da plataforma refere-se ao levantamento das possibilidades e limitações tecnológicas do ambiente no qual o sistema interativo será executado. Inserida na fase de Análise de Requisitos do ciclo de vida da Engenharia de Usabilidade de Mayhew, esta etapa é fundamental para guiar as decisões arquiteturais antes do desenho de qualquer tela. 

A análise a seguir documenta a realidade tecnológica do elenco de personas definido para o projeto, baseando-se nas restrições do que o portal atual da Fundação Hemocentro de Brasília (FHB) oferece e nas demandas tecnológicas exigidas pelas novas funcionalidades que estão sendo propostas.

### 1. Características

#### Funcionalidades e Recursos Atuais
Atualmente, o portal da Fundação Hemocentro de Brasília opera predominantemente como um repositório informacional e um portal de triagem de acesso. Seus principais recursos englobam:

- Disponibilização de cartilhas informativas e critérios de doação.
- Acesso a documentos estáticos (arquivos em formato PDF) para preenchimento manual por unidades conveniadas.
- Menu de navegação institucional, transparência e ouvidoria.
- Links de redirecionamento externo para serviços de terceiros (agendamentos e formulários paralelos).

#### Características Faltantes (Propostas de Intervenção)

Para atender aos objetivos dos perfis de usuários mapeados, a plataforma carece da internalização de serviços críticos, tais como:

- Um módulo integrado para o agendamento de Doação em Grupo, eliminando a dependência do canal de WhatsApp.
- Uma funcionalidade nativa para a emissão digital da "Carteirinha de Identificação da Doença Falciforme", mantendo os pacientes dentro do ecossistema do Hemocentro.
- Um sistema digitalizado para o Formulário de Investigação de Reação Transfusional (FIRT), substituindo a burocracia de impressão e escaneamento por envios diretos via sistema com confirmação imediata.

### 2. Limitações de Hardware (Equipamentos)

As decisões de design devem considerar a extrema heterogeneidade dos dispositivos utilizados pelos atores do sistema:

- **Ambiente Clínico/Hospitalar:** O acesso se dará primordialmente por computadores *desktop* (de mesa) pertencentes à rede pública de saúde. Estes equipamentos costumam apresentar configurações de hardware defasadas, monitores com resoluções menores e periféricos (mouses e teclados) desgastados pelo uso contínuo, o que exige alvos de clique (botões) grandes e fluxos tolerantes a erros motores.
- **Ambiente Externo/Cidadão:** O acesso será majoritariamente *mobile-first*. A interface deve ser plenamente responsiva, adaptando-se do celular mais moderno ao mais básico.

### 3. Limitações de Software e Navegadores

Para garantir a acessibilidade e a compatibilidade universal:

- **Sistemas Operacionais:** A plataforma deve operar perfeitamente em computadores com Windows e distribuições Linux (comuns em órgãos do Governo do Distrito Federal), além de rodar nos sistemas móveis Android e iOS.
- **Navegadores (Browsers):** O sistema deve ser homologado para os navegadores mais populares: Google Chrome, Safari, Mozilla Firefox e Microsoft Edge.
- **Restrições de Instalação:** O design deve ser puramente baseado na Web (*Web-based*). É estritamente proibido exigir que o usuário instale programas extras, executáveis ou *plugins* modernos de terceiros, uma vez que as políticas de segurança da tecnologia da informação (TI) dos hospitais frequentemente bloqueiam essas instalações.

### 4. Restrições de Conectividade e Desempenho

A infraestrutura de rede varia drasticamente dependendo do contexto do usuário:

- **Dados Móveis Limitados:** Usuários em mobilidade ou com vulnerabilidade socioeconômica podem operar sob pacotes de dados 3G/4G restritos ou intermitentes. 
- **Desempenho:** A plataforma não deve conter vídeos de carregamento automático pesados, imagens sem otimização ou animações complexas em JavaScript que gerem lentidão na renderização. O tempo de resposta deve ser ágil para não causar a evasão do usuário.
- **Restrições de Dispositivos de Saída (Output):** A plataforma não pode depender de dispositivos de saída de áudio para emitir alertas críticos. Todo o feedback do sistema deve ser estritamente visual, com alto contraste e confirmações textuais em tela.

### 5. Entraves Atuais da Plataforma

A fragmentação dos serviços é o maior entrave de interação da atualidade. O sistema delega tarefas críticas a plataformas externas, gerando sobrecarga cognitiva e a quebra da jornada do usuário. Os principais gargalos são:

- **Redirecionamento Confuso para Agendamento:** Ao clicar em "Agende sua doação", o usuário é expulso do ambiente do Hemocentro e direcionado ao "Agenda DF". Nesta plataforma genérica governamental, o usuário é bombardeado por logomarcas não relacionadas à saúde (como Procon, Defensoria, Receita Federal, etc.), causando desorientação, perda de foco e a sensação de que navegou para o local errado.
- **Autenticação Desnecessariamente Complexa:** A plataforma de agendamento externa exige obrigatoriamente *login* integrado no portal `gov.br` ou no "Participa DF". Para usuários jovens apressados ou idosos de baixo letramento digital, a necessidade de relembrar senhas complexas governamentais apenas para marcar uma doação de sangue atua como uma barreira severa (*pain point*), resultando frequentemente no abandono da tarefa solidária.
- **Redundância de Passos:** O sistema atual ("Agenda DF") obriga o cidadão a selecionar o posto de atendimento de forma manual, mesmo havendo apenas uma única opção disponível em todo o Distrito Federal (FHB - Asa Norte), o que gera cliques inúteis e frustração.
- **Fuga para Formulários Genéricos:** A emissão de carteirinhas ou registros expulsa o paciente para plataformas de terceiros, como o *Google Forms*, quebrando a credibilidade, a identidade visual e a segurança institucional da jornada.

---

## Bibliografia

> <a id="ref1"></a> [1] BARBOSA, Simone Diniz Junqueira et al. *Interação Humano-Computador e Experiência do Usuário*. 1. ed. Rio de Janeiro: Autopublicação, 2021.

> <a id="ref1"></a> [2] FUNDAÇÃO HEMOCENTRO DE BRASÍLIA. Página Inicial. Brasília, DF, 2026. Disponível em: <https://www.fhb.df.gov.br/>. Acesso em: 03 maio 2026.

## Histórico de Versões

| Versão | Descrição | Data | Autor(es) | Data de revisão | Revisor(es) |
| :---: | :--- | :---: | :---: | :---: | :---: |
| 1.0 | Criação do Documento | 03/05/2026 | [Pedro Américo](https://github.com/dev-americo)| 03/05/2026 | [Lucas Oliveira](https://github.com/dev-LucasDpaula) |
| 1.1 | Revisão do características | 11/05/2026 | [Pedro Américo](https://github.com/dev-americo)| 11/05/2026 | [Lucas Oliveira](https://github.com/dev-LucasDpaula) |