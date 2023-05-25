## Display Property Project

#### Setup

- create folder (06-display-property)
- create index.html, general structure
- give it a title (display property)
- create css file (main.css)
- link to css file in html (head element)

#### HTML (structure)

- create div with class "section"
  - inside setup
    - div with class "section-title"
      - inside setup
      - h1
      - div with class "title-underline"
    - div with class "section-center"
      - inside setup
      - p

#### CSS (styles)

- setup reset
- select body, add system fonts, background (#f1f5f9), line height

- select section, add padding, background (#fff)

- select "section-title", add text-align, text-transform

- select .title-underline, add height, width, background, place in the center, add margin in the bottom

- select section center, add width (90vw), max-width (1170px), place in the center

#### Questions

- Why section title in a separate div?
  - Está separado por uma questão de reusabilidade, é como se fosse um componente que pode ser copiado e colado, isso facilita o desenvolvimento
- Why 90vw and 1170px?
  - 90vw - é para sempre ocupar um mesmo espaço independente do dispositivo, responsividade e consistencia
  - max-width: 1170px - ter um tamanho máximo para ser que se o dispositivo for muito grande facilitar a leitura
- The purpose of section-center
  - pois a largura de section será do tamanho da tela com o background branco, e section-center vai estar centralizado com um tamanho limitado e com o conteúdo
