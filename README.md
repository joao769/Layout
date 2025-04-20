# 🎨 Layout Responsivo com Flexbox e CSS Grid

## 📝 Sobre o Projeto

Este repositório apresenta dois projetos focados em layouts responsivos, utilizando Flexbox e CSS Grid, como parte da disciplina Programação para Web do curso de Engenharia de Software da UPE. As atividades foram propostas pelo professor Augusto César, com o objetivo de comparar as abordagens e destacar as vantagens de cada técnica.

## ✨ Características

### Projeto 1 — Flexbox
- Layout vertical no `<body>` com `flex-direction: column`.
- Divisão do conteúdo principal com Flexbox horizontal.
- Uso de `gap`, `justify-content`, `align-self`, `flex`.
- Alinhamento do `<header>` com Flexbox.
- Responsivo com media queries e carrossel lateral em `<aside>` para telas menores.

### Projeto 2 — CSS Grid + Flexbox
- Layout geral com CSS Grid: `<header>`, `<main>` e `<footer>` em linhas.
- Colunas no `<main>` com `grid-template-columns`.
- Seções internas divididas com CSS Grid.
- Flexbox usado para alinhar conteúdos do `<header>` e `<aside>`.
- Estrutura adaptável com carrossel horizontal em telas menores.

## 🔎 Diferenças Percebidas

| Aspecto                           | Apenas Flexbox                                                        | CSS Grid + Flexbox                                                            |
|-----------------------------------|------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| Estrutura do layout               | Organização mais linear, ideal para layouts em uma única direção       | Permite definir áreas com mais precisão, criando grades e divisões complexas |
| Facilidade para layouts complexos | Pode exigir soluções alternativas com `margin` e `order`               | Mais direto e visual para distribuir áreas como header, sidebar e footer     |
| Controle de eixos                 | Trabalha melhor em um eixo por vez (horizontal ou vertical)            | Controle total nos dois eixos (linha e coluna) ao mesmo tempo                |
| Uso do Flexbox                    | Total, tanto para estrutura quanto para conteúdo interno               | Usado principalmente para alinhar e distribuir elementos dentro das áreas    |

## 🌍 Visualização

👉 [Visualize os projetos aqui](https://joao769.github.io/layout-responsivo-css/)