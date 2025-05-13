# Resumo do Projeto: Formulário de Criação de Evento

Este projeto consiste em uma página web para criar e compartilhar eventos, utilizando HTML e CSS. O objetivo principal foi praticar a criação de formulários acessíveis, estilização avançada com CSS e organização de layouts responsivos.

## O que foi feito

- Estruturação de um formulário completo para cadastro de eventos, com campos para título, link, WhatsApp, informações extras, categoria, privacidade, e data/horário.
- Utilização de diferentes tipos de campos (`text`, `url`, `number`, `email`, `password`, `date`, `time`, `textarea`, `select`, `checkbox`).
- Validação básica de campos obrigatórios e restrições de tamanho/minlength.
- Estilização detalhada com CSS, incluindo:
  - Layout centralizado e responsivo.
  - Uso de fontes externas (Google Fonts).
  - Personalização de campos, botões e checkbox.
  - Efeitos visuais para foco, hover e campos inválidos.
  - Separação visual dos fieldsets com legendas e divisórias.
- Organização do código para facilitar manutenção e leitura.

## Como foi feito

- O HTML foi estruturado com semântica, utilizando `<form>`, `<fieldset>`, `<legend>`, `<label>`, e agrupando inputs em wrappers para facilitar o CSS.
- O CSS foi utilizado para criar um visual moderno, com cores, espaçamentos, bordas arredondadas e responsividade.
- Foram aplicadas técnicas de customização de elementos nativos, como o select e o checkbox, usando imagens SVG embutidas via `background-image`.
- A validação dos campos foi feita utilizando atributos HTML (`required`, `minlength`, `type`), e o CSS destaca campos inválidos.
- O botão de submit foi posicionado fora do `<form>` usando o atributo `form`, permitindo um footer fixo e estilizado.

## Pontos de estudo

- Como estruturar formulários complexos e acessíveis.
- Customização de elementos de formulário com CSS puro.
- Uso de Google Fonts e variáveis de fonte.
- Técnicas de centralização e responsividade em layouts.
- Separação de responsabilidades entre HTML (estrutura) e CSS (estilo).

---
Este resumo serve como referência rápida para revisar as principais técnicas e decisões tomadas neste projeto.
