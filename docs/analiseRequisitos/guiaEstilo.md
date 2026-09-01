# Guia de Estilo: Módulo Digital do Hemocentro de Brasília (FHB)

## <a id="introducao"></a>1. Introdução

- **Origem**: Esse guia de estilo levou em conta as metas de usabilidade exigidas no documento [Metas de Usabilidade](../../../analiseRequisitos/metasUsabilidade)
- **Objetivo do guia de estilo:** Consolidar a identidade visual e os padrões de interação do portal da FHB, refletindo a união entre solidariedade, ciência e excelência. Garantir a consistência e padronização [[1]](#ref1) da interface, fundamentais para uma experiência do usuário satisfatória, reduzindo o tempo de aprendizado e prevenindo erros críticos no fluxo hospitalar.
- **Público-alvo:** Designers de IHC, desenvolvedores front-end e gerentes de produto envolvidos na construção e manutenção das funcionalidades do portal institucional e da área de Unidades Conveniadas.
- **Como utilizar:** Como documento de consulta obrigatória para a padronização de novas telas, garantindo a consistência visual (look-and-feel). Ele serve como uma ferramenta prática de comunicação entre os membros da equipe de design e os programadores [[1]](#ref1), assegurando que o sistema final reflita os princípios de IHC.
- **Como manter:** Este guia deve ser mantido atualizado no repositório central da equipe (ex: Notion/Figma) e ser revisado a cada nova sprint de desenvolvimento, garantindo que as decisões de design não se percam.

## <a id="metodologia"></a>2. Metodologia

A definição deste guia baseou-se em um processo de design centrado no usuário [[1]](#ref1), focado na compreensão aprofundada dos usuários, seu ambiente e contexto de uso.

Inicialmente, foram realizadas análises para caracterizar os perfis de usuários e criar personas, identificando suas necessidades e limitações cognitivas e motoras [[1]](#ref1). Essa análise documental guiou a escolha dos elementos de interface e interação, visando maximizar a usabilidade. O desenvolvimento deste guia é parte integrante de um ciclo de engenharia de usabilidade [[1]](#ref1), onde as diretrizes aqui definidas serão aplicadas em protótipos e posteriormente avaliadas junto aos usuários.

## <a id="resultado-da-analise"></a>3. Resultado da Análise

- **Descrição do ambiente de trabalho do usuário:** Os usuários principais atuam na linha de frente de prontos-socorros e hospitais conveniados. O ambiente é caótico, com interrupções frequentes e altíssima carga cognitiva e de estresse.
- **Contexto de Uso:** O acesso ocorre via computadores desktop de forma esporádica e sob severa pressão de tempo. A interface deve priorizar a eficiência máxima, legibilidade rápida e prevenção ativa de erros críticos, como na digitação de laudos de compatibilidade imunológica.

## <a id="elementos-de-interface"></a>4. Elementos de Interface

- **Tipografia Institucional:** A fonte oficial do Hemocentro é a MR Eaves XL Mod OT. Ela deve ser utilizada em títulos, chamadas de destaque e informações prioritárias para transmitir modernidade e legibilidade [[2]](#ref2).

- **Cores Oficiais:**
    - Vermelho Hemocentro: <span style="display: inline-block; width: 16px; height: 16px; background-color: #D51317; border-radius: 3px; vertical-align: middle; margin-right: 5px; border: 1px solid #ccc;"></span> HEX #D51317 (RGB: 213, 19, 23). Cor principal, transmite vitalidade e urgência [[2]](#ref2).
    - Grafite Hemocentro: <span style="display: inline-block; width: 16px; height: 16px; background-color: #3C3C3B; border-radius: 3px; vertical-align: middle; margin-right: 5px; border: 1px solid #ccc;"></span> HEX #3C3C3B (RGB: 60, 60, 60). Cor de apoio e para textos de leitura, proporcionando alto contraste sem o peso do preto absoluto [[2]](#ref2).
    - Branco Hemocentro: <span style="display: inline-block; width: 16px; height: 16px; background-color: #FFFFFF; border-radius: 3px; vertical-align: middle; margin-right: 5px; border: 1px solid #ccc;"></span> HEX #FFFFFF (RGB: 255, 255, 255). Fundo padrão para garantir o "respiro" visual.

- **Símbolos e Logomarca (A Gota):**
    - A marca da FHB (gota estilizada) deve ter o tamanho mínimo de 3 cm de largura (com assinatura) ou 1,5 cm (sem assinatura) [[2]](#ref2).
    - A distância mínima de respiro em relação a outras marcas deve ser equivalente à altura da letra "H" da marca do Hemocentro [[2]](#ref2).
    - Usos indevidos: É obrigatório manter as características originais da marca. É terminantemente proibido rotacionar, usar como marca d'água, aplicar moldura ou alterar as cores institucionais do logotipo [[2]](#ref2).
    - Fundos Diversos e Versões Monocromáticas: Quando a marca for aplicada sobre fundos de cores não institucionais, recomenda-se o uso da versão monocromática (preta, branca ou vermelha), devendo ser escolhida de acordo com o contraste necessário para garantir a melhor visibilidade e legibilidade. Caso a logomarca precise ser aplicada sobre uma imagem ou um fundo conturbado, é exigido o uso da versão com fundo mínimo branco ou vermelho, também dependendo do contraste com a imagem de fundo.

- **Disposição Espacial (Layout):** Telas limpas (estilo minimalista) para que o usuário hospitalar encontre as informações de urgência rapidamente, evitando poluição visual.
- **Janelas:** O formato das janelas secundárias (modais/pop-ups) será utilizado apenas para confirmações críticas (ex: envio de laudos). Elas devem sobrepor a tela principal escurecendo o fundo (overlay) e conter um botão claro de saída ("X").
- **Símbolos não tipográficos:** A padronização visual dos ícones seguirá a regra: ícones de ação primária serão preenchidos (solid), enquanto ícones de navegação inativos ou secundários serão vazados (outline).
- **Animações:** Uso estritamente funcional. Restritas a transições de feedback rápido, como a mudança de cor de um botão quando o mouse passa por cima (hover). Evitar animações longas que atrasem o fluxo de urgência.

## <a id="elementos-da-interacao"></a>5. Elementos da Interação

- **Estilos de Interação:** Predominância de interação por formulários e menus. Como o objetivo é preencher dados clínicos estruturados, os formulários devem ser divididos em grupos lógicos e seguir o fluxo natural de leitura top-down.
- **Seleção de um estilo:** Usaremos a lógica de densidade. Para uso hospitalar em desktop, usaremos barras laterais fixas que comportam muita informação. Para acesso móvel de doadores, usaremos menus responsivos contraídos.
- **Aceleradores (teclas de atalho):** Essenciais para a eficiência de usuários experientes. Uso de autocompletar para termos técnicos e atalhos de teclado (ex: `Enter` para submeter, `Esc` para fechar).

## <a id="elementos-de-action"></a>6. Elementos de Ação

- **Preenchimento de Campos:** A interface deve utilizar restrições (ex: validação em tempo real) e máscaras automáticas. Campos obrigatórios serão sinalizados com asterisco (*). O sistema deve trazer opções pré-preenchidas com valores padrão inteligentes (defaults).
- **Ativação e Feedback:** Os botões de ação primária devem utilizar o Vermelho Hemocentro. O sistema deve emitir respostas claras e imediatas de feedback (ex: Alerta verde: "Solicitação recebida") após a execução da ação.
- **Projeto para Erros:** Controles "perigosos" (como "Cancelar requisição") devem ficar fisicamente afastados dos botões de salvamento. Mensagens de erro devem ser simples, construtivas e fornecer meios para o usuário se recuperar.
- **Seleção:** Quando o usuário puder escolher várias opções, utilizaremos checkboxes. Quando a escolha for estritamente única e mutuamente exclusiva, usaremos radio buttons.

## <a id="vocabulario-e-padroes"></a>7. Vocabulário e Padrões

- **Terminologia:** A interface deve espelhar o modelo mental dos especialistas. Utilizar jargão médico familiar na área hospitalar. Na área pública, o sistema chamará o usuário de "Doador" ou "Paciente" conforme o contexto.
- **Sequências de Diálogos:** Manter a coerência e o tom de voz das mensagens. Diálogos de alerta antes de submissões críticas para confirmar dados da solicitação urgente. As mensagens não devem conter conteúdos irrelevantes.
- **Sistema de Ajuda:** O sistema de ajuda atuará como uma forma de comunicação direta entre o design e o usuário, devendo ser oferecido de forma contextual, em camadas e sob demanda.
    - Sob demanda e contextual: O apoio será acionado apenas quando o usuário requisitar, estando posicionado exatamente no elemento da interface que gera a dúvida (ex: ícones de "?" ao lado de campos complexos em formulários médicos).
    - Foco nas dúvidas frequentes: O conteúdo da ajuda será formulado para responder às perguntas reais do usuário. Dúvidas descritivas ("O que é isto?" ou "Para que serve isto?") serão sanadas por meio de tooltips breves e diretos.
    - Ajuda em camadas: Para dúvidas procedimentais ou de escolha ("Como eu faço isto?" ou "O que posso fazer agora?"), a ajuda deverá apresentar uma primeira camada com instruções rápidas e fornecer acesso (links ou expansões) para uma segunda camada com tutoriais ou passo a passo detalhado para a recuperação de erros, sem retirar o usuário do seu contexto de trabalho.
- **Tipos de tela:** Padrões visuais repetitivos: Toda tela de formulário médico terá o botão principal de envio (vermelho) fixado no canto inferior direito.

## Referência Bibliográfica

<a id="ref1"></a>[[1]](#introducao) BARBOSA, S. D. J., & SILVA, B. S. da. **Interação Humano-Computador**. Rio de Janeiro: Elsevier, 2010.

<a id="ref2"></a>[[2]](#elementos-de-interface) FUNDAÇÃO HEMOCENTRO DE BRASÍLIA. **Manual de Aplicação da Logomarca**. Brasília, DF: FHB, 2025. Disponível em: <https://fhb.df.gov.br/documents/d/fhb/manual-de-aplicacao-da-logomarca-fundacao-hemocentro-de-brasilia_compressed-1-pdf>. Acesso em: 03 mai. 2026.

## Bibliografia

## Histórico de Versões

| Versão | Descrição | Data | Autor(es) | Data de revisão | Revisor(es) |
| :---: | :--- | :---: | :---: | :---: | :---: |
| 1.0 | Criação do Guia de Estilo | 02/05/2026 | [Pedro Lucas](https://github.com/Pwdrinho) | 03/05/2026 | [Breno Teixeira](https://github.com/BrenoLTeixeira) |
| 2.0 | Complementação do Guia de Estilo | 03/05/2026 | [Breno Teixeira](https://github.com/brenolteixeira) | 03/05/2026 | [Pedro Lucas](https://github.com/Pwdrinho) |
| 3.0 | Atualização do Guia de Estilo | 30/06/2026 | [Lucas Oliveira](https://github.com/dev-LucasDpaula) | 30/06/2026 | [Pedro Ian](https://github.com/pedroiaan) |