# Pokedex Responsiva - Atividade de Layout e Responsividade

Este projeto e uma aplicacao web desenvolvida como parte da atividade pratica de Front-End, focada na construcao de layouts adaptaveis e responsivos utilizando CSS3 modernizado (Flexbox, CSS Grid e Media Queries) sob a abordagem Mobile-First.

---

## Indice

- [Sobre o Projeto](#sobre-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Requisitos Atendidos](#requisitos-atendidos)
- [Como Executar o Projeto](#como-executar-o-projeto)
- [Estrutura de Arquivos](#estrutura-de-arquivos)

---

## Sobre o Projeto

A interface consiste em um portal tematico do universo Pokemon, apresentando um menu de navegacao superior, uma galeria interativa de imagens e uma secao de informacoes detalhadas organizada em formato de cartoes. O objetivo principal e garantir a navegabilidade fluida e a correta adaptacao visual em dispositivos moveis e telas de alta resolucao.

---

## Funcionalidades

- **Navegacao por Âncoras:** Clique na imagem do Pokemon na galeria para ser redirecionado diretamente ao card com as informacoes e tipos correspondentes.
- **Rolagem Suave:** Transicao automatica e suave entre as secoes da pagina.
- **Layout Adaptavel (Mobile-First):** Exibicao otimizada em uma unica coluna para smartphones, ajustando-se dinamicamente para multiplas colunas em telas maiores.

---

## Tecnologias Utilizadas

- **HTML5:** Estruturacao semantica das secoes (`<main>`, `<nav>`, `<section>`, `<article>`).
- **CSS3:** Estilizacao visual, leiaute dinamico e responsividade.

---

## Requisitos Atendidos

De acordo com as diretrizes da avaliacao, o projeto implementa os seguintes conceitos:

1. **Uso da propriedade `display`:** Aplicacao adequada de `block`, `inline-block`, `flex` e `grid` ao longo de toda a estrutura.
2. **Flexbox:** Empregado no menu de navegacao (`.menu`) e na galeria de imagens (`.pokemon`), fazendo uso das propriedades `display: flex`, `flex-direction`, `justify-content`, `align-items`, `gap` e `flex-wrap`.
3. **CSS Grid:** Utilizado na secao de cartoes informativos (`.grid-cartoes`) com `display: grid`, `grid-template-columns` e `gap`.
4. **Responsividade e Media Queries:** Implementada breakpoint a partir de `min-width: 768px` para reorganizacao de elementos em telas de tamanho medio e grande.
5. **Abordagem Mobile-First:** O CSS base foi estruturado focando inicialmente na visualizacao mobile e expandido via Media Queries.
6. **Configuracao de Viewport:** Declaracao da meta tag `<meta name="viewport" content="width=device-width, initial-scale=1.0">` no cabecalho do documento.
7. **Unidades Relativas:** Utilizacao consciente de `rem`, `%` e `fr` em substituicao ao uso fixo em pixels (`px`).

---

## Como Executar o Projeto

1. Clone o repositorio para a sua maquina local:
   ```bash
   git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)

2. Acesse a pagina do projeto
   cd seu-repositorio

3. Abra o arquivo index.html em qualquer navegador web de sua preferencia ou utilize a extensao Live Server no VS Code.
Estrutura dos arquivos
/
├── index.html
├── style.css
├── imagens-nav/
│   ├── Inicio-9-8-2026.png
│   ├── Principais-Pokemon-9-8-2026.png
│   └── Sobre-N-s-9-8-2026.png
└── imgs-pokemon/
    ├── pikachu.jpg
    ├── eevee.png
    ├── bulbasaur.jpg
    ├── ponyta.png
    └── charmander.png

   
