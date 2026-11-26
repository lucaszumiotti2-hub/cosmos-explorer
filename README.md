# Cosmos Explorer | Espaço Cibernético

**Plataforma web educativa de astronomia · Versão 1.0**

Explore oito constelações, navegue pelo Sistema Solar e teste seus conhecimentos em um quiz interativo. O Cosmos Explorer é um projeto acadêmico demonstrativo de **Análise e Desenvolvimento de Sistemas** e integra o portfólio profissional de Lucas Zumiotti.

[**Abrir demonstração online**](https://lucaszumiotti2-hub.github.io/cosmos-explorer/) · [**Ver código-fonte**](./index.html)

## Objetivo

Apresentar conceitos introdutórios de astronomia por meio de diagramas, fichas informativas e atividades interativas. O projeto aplica fundamentos de desenvolvimento front-end à organização de conteúdo educativo e à criação de uma interface responsiva que funciona diretamente no navegador.

## Funcionalidades

| Módulo | O que você pode fazer |
| --- | --- |
| **Atlas de constelações** | Explorar oito constelações, buscar pelo nome, exibir ou ocultar o traçado e os nomes das estrelas e salvar favoritas no navegador. |
| **Sistema Solar** | Selecionar um dos oito planetas no diagrama ou na lista, consultar sua ficha e ativar a animação das órbitas. |
| **Biblioteca astronômica** | Consultar cartões ilustrados sobre galáxias, nebulosas, buracos negros, estrelas, exoplanetas e aglomerados estelares. |
| **Quiz** | Responder a cinco perguntas, receber feedback, acompanhar a pontuação e reiniciar a atividade. |

## Demonstração e destaques visuais

[**Acessar o Cosmos Explorer no GitHub Pages**](https://lucaszumiotti2-hub.github.io/cosmos-explorer/)

- **[Atlas celeste](https://lucaszumiotti2-hub.github.io/cosmos-explorer/#atlas)** — Abra Órion, alterne os nomes das estrelas e salve a constelação como favorita.
- **[Sistema Solar](https://lucaszumiotti2-hub.github.io/cosmos-explorer/#solar)** — Selecione Saturno para consultar sua ficha e use o controle de animação para visualizar as órbitas esquemáticas.
- **[Quiz](https://lucaszumiotti2-hub.github.io/cosmos-explorer/#quiz)** — Responda às perguntas para acompanhar o feedback e a pontuação.

A interface combina tema escuro, ilustrações em CSS e diagramas em SVG. O layout se adapta a telas menores e oferece indicadores de foco visíveis para navegação por teclado.

## Tecnologias utilizadas

| Tecnologia | Aplicação no projeto |
| --- | --- |
| **HTML5** | Estrutura das seções, navegação e controles da interface. |
| **CSS3** | Layout responsivo, tema visual e ilustrações. |
| **JavaScript** | Busca e filtros, seleção de planetas, animação orbital e lógica do quiz. |
| **SVG** | Diagramas das constelações e das órbitas planetárias. |
| **Web Storage (`localStorage`)** | Persistência dos favoritos no navegador. |
| **GitHub Pages** | Hospedagem da aplicação estática. |

## Como executar localmente

1. Clone o repositório ou baixe o ZIP pelo menu **Code → Download ZIP** do GitHub.
2. Abra o arquivo `index.html` em um navegador moderno.

```bash
git clone https://github.com/lucaszumiotti2-hub/cosmos-explorer.git
cd cosmos-explorer
```

A aplicação roda diretamente no navegador, sem instalar dependências ou executar uma etapa de build.

## Publicação no GitHub Pages

1. No repositório, abra **Settings → Pages**.
2. Em **Build and deployment**, escolha **Deploy from a branch**.
3. Selecione a branch **`main`** e a pasta **`/ (root)`**.
4. Clique em **Save** e, após a publicação, use o endereço exibido na seção **Pages**.

[Documentação oficial do GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## Estrutura de arquivos

Na versão 1.0, o `index.html` reúne a marcação HTML, os estilos, os scripts, os dados didáticos e os diagramas.

```text
cosmos-explorer/
├── index.html
└── README.md
```

Uma organização sugerida para futuras versões é mover os estilos para `assets/css/`, os scripts para `assets/js/` e as capturas de tela da demonstração para `docs/img/`.

## Competências desenvolvidas

- Estruturação de conteúdo educativo em HTML e criação de layouts responsivos em CSS.
- Manipulação do DOM e tratamento de eventos para busca, filtros e controles da interface.
- Representação visual de dados com SVG e atualização dos diagramas com JavaScript.
- Gerenciamento do progresso e da pontuação do quiz, com feedback a cada resposta.
- Persistência de preferências no navegador e documentação da execução e da publicação.

## Limitações

- Os mapas celestes são esquemáticos. As órbitas, dimensões e distâncias na visualização do Sistema Solar estão fora de escala.
- A plataforma funciona como recurso didático e não oferece a precisão de um planetário. Não há efemérides em tempo real nem cálculo de visibilidade por data e localização.
- A aplicação é estática, sem backend ou autenticação. Os favoritos ficam no navegador em que foram salvos.

## Contexto acadêmico

**Responsável pelo portfólio** — Lucas Zumiotti  
**Formação** — Análise e Desenvolvimento de Sistemas, em andamento  
**Desenvolvimento** — Protótipo acadêmico desenvolvido com auxílio de IA.

## Referências

- [NASA — Planetas do Sistema Solar](https://science.nasa.gov/solar-system/planets/)
- [NASA — Universo](https://science.nasa.gov/universe/)
- [União Astronômica Internacional (IAU)](https://www.iau.org/)
