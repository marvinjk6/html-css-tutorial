## Fonts

- google fonts
- catamaran
- grand hotel

## Global styles

- O projeto está sendo pensado no estilo "Mobile First"
- o tamanho da fonte vai mudar quando chegar a 800px, definido em media queries

## Additional Video
- é um link para um vídeo que tem explicações sobre a função translate()
- https://www.youtube.com/watch?v=_gu_2sqkFPk

## Content divider
é uma div com linear-gradient

## Skills Columns and Clearfix

- para dispositivos pequenos skills ficará um em baixo do outro (que é o padrão Mobile First)
- para dispositivos médio skills terá duas colunas e duas linhas
- para dispositivos muito quande, ficará um do lado do outro
 
Será usado a propriedade float, futuramente flex-box ou grid

## Navbar funcionality

- primeiro a classe navbar que está sendo aplicada terá tranform: translateX(-100%); o que vai remover o navbar
- a classe showNav será aplicada dinamicamente com javascript, tranform: translate(0) que mostrará o navbar

## Animation

O projeto terá 4 animações:

- Primeira animação:
   * o nome da animação é bounce
   * animação colocada em .nav-btn
- Segunda animação:
   * o nome da animação é slideFromRight
   * animação colocada em banner h2
- Terceira animação:
   * o nome da animação é slideFromLeft
   * animação colocada em banner h1
- Quarta animação:
   * o nome da animação é show
   * animação colocada em banner-btn