# KOVR

**Disciplina gera progresso.**

KOVR é a proposta de um aplicativo mobile para acompanhar treinos de
academia, criar uma rotina consistente e visualizar a própria evolução.
O projeto será desenvolvido com foco em uma experiência simples de usar
durante o treino e uma identidade visual industrial, tecnológica e
elegante.

> **Status:** fase de planejamento e definição da identidade visual. A
> paleta, a direção da marca e as fontes foram escolhidas; as telas e
> funcionalidades ainda precisam ser desenvolvidas.

## Objetivos do projeto

-   Registrar os dias em que fui à academia.
-   Criar e organizar planos de treino.
-   Cadastrar exercícios, cargas, séries e repetições.
-   Acompanhar os exercícios durante um treino.
-   Consultar o histórico e visualizar a evolução ao longo do tempo.
-   Configurar lembretes para ajudar a manter a consistência.
-   Permitir a escolha entre tema claro e tema escuro.

## Identidade visual

### Nome

**KOVR**

Nome curto, forte e adequado a uma marca com personalidade técnica e
contemporânea.

### Conceito

A direção visual combina:

-   Estética industrial e tecnológica.
-   Logo geométrica e angular, com um símbolo reduzido baseado na letra
    **K**.
-   Interface organizada, com hierarquia visual clara.
-   Ênfase em consistência, disciplina e progresso, sem depender de
    clichês visuais de aplicativos fitness.

### Paleta oficial --- Plum Tech

A paleta foi inspirada no tom ameixa/vinho do iPhone mostrado durante a
exploração visual. O ameixa é a cor principal da marca; as outras cores
equilibram a interface.

  -----------------------------------------------------------------------
  Cor                     Hexadecimal             Uso previsto
  ----------------------- ----------------------- -----------------------
  **Plum**                `#713D59`               Cor principal da marca
                                                  e elementos de
                                                  identidade

  **Graphite**            `#17171C`               Fundo principal do tema
                                                  escuro

  **Steel**               `#3A3F4A`               Superfícies, cartões e
                                                  componentes

  **Cloud**               `#C9CDD3`               Textos e elementos
                                                  claros no tema escuro

  **Ice**                 `#8FD3D6`               Destaques pontuais,
                                                  indicadores e progresso
  -----------------------------------------------------------------------

**Diretriz de uso:** o ameixa deve continuar sendo a cor mais
reconhecível da KOVR. O azul-gelo deve ser usado com moderação, para
indicadores, progresso e estados ativos.

A versão clara deverá usar fundos claros e neutros, mantendo o ameixa
como assinatura visual. Os valores e contrastes finais devem ser
validados durante a implementação.

### Tipografia

-   **Barlow Condensed:** títulos, números e destaques.
-   **Archivo:** textos, formulários e elementos da interface.

### Logo e ícone

A direção escolhida é uma logo angular, com lettering geométrico para
"KOVR" e uma versão reduzida com o símbolo **K** para o ícone do
aplicativo. O conceito visual do ícone foi explorado com fundo ameixa
escuro e símbolo claro.

Os arquivos gerados durante a exploração visual são referências de
design. Antes de usar em produção, vale preparar versões finais em alta
resolução e, idealmente, um arquivo vetorial (SVG).

## Experiência do aplicativo

As telas planejadas para orientar o desenvolvimento são:

1.  **Início:** resumo do próximo treino, acesso rápido para começar e
    visão geral do progresso.
2.  **Treinos:** planos organizados por grupo muscular ou rotina, com
    lista de exercícios.
3.  **Treino em andamento:** registro de séries, repetições e cargas,
    com fluxo simples para avançar entre exercícios.
4.  **Evolução:** histórico de treinos e visualizações de progresso,
    como mudanças de carga e frequência.
5.  **Configurações:** tema claro/escuro, lembretes e preferências do
    aplicativo.

Essas telas são uma direção inicial de produto, não funcionalidades já
implementadas.

## Tecnologias planejadas

-   **Flutter** para desenvolver o aplicativo mobile.
-   **Dart** como linguagem principal.
-   **Windows** como ambiente de desenvolvimento.
-   **Galaxy S24** como dispositivo inicial para testar a experiência.

A arquitetura, a persistência dos dados e a estratégia de notificações
ainda precisam ser definidas. Não foi decidido se os dados ficarão
somente no dispositivo ou se haverá sincronização em nuvem.

## Próximos passos

-   [ ] Refinar a logo e exportar os arquivos finais.
-   [ ] Definir os tokens de design para temas claro e escuro.
-   [ ] Desenhar as telas principais com a paleta Plum Tech.
-   [ ] Criar o projeto Flutter e organizar sua estrutura.
-   [ ] Implementar navegação e componentes reutilizáveis.
-   [ ] Modelar treinos, exercícios, séries, repetições e cargas.
-   [ ] Implementar o registro de treinos e o histórico.
-   [ ] Criar visualizações de progresso.
-   [ ] Implementar lembretes e preferências de tema.
-   [ ] Testar no Galaxy S24 e ajustar usabilidade e acessibilidade.

## Princípios de design

-   **Clareza durante o treino:** as informações importantes devem ser
    fáceis de consultar rapidamente.
-   **Poucos passos:** registrar uma série ou concluir um exercício não
    deve exigir navegação desnecessária.
-   **Progresso visível:** facilitar a comparação do desempenho ao longo
    do tempo.
-   **Personalização:** permitir tema claro ou escuro.
-   **Consistência visual:** usar a paleta e a tipografia de forma
    previsível em todas as telas.

------------------------------------------------------------------------

*Documento de referência criado em 26 de outubro de 2026, com o resumo
das decisões de produto e identidade visual definidas até agora.*
