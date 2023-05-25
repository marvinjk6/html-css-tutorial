## Position Property Project

#### Setup

- copy last project
- rename to (08-position-property)
- change title (Position Property)

#### HTML (structure)

- add div with class of "temp" at the end of the html document (still inside the body)

#### CSS (styles)

- set .temp (min-heigth:100vh), so scroll works
- set nav sticky (position,top,z-index)
- set .hero on small screen only with color background, starting with 768px add current (image background)
- add position relative to .hero
- set .hero-center position absolute and place in the center (gotcha - section 19)


#### Anotações

- hero está com potition: relative, devido a isso em nav que está com position sticky a navegação não vai aparecer quando usar o scroll devido as posições dos elementos que não estão no fluxo normal
   * para resolver isso, usar o z-index passando um valor positivo em nav
- hero-center vai ter position: absolute
   * top: 50%
   * left: 50%
   * transform: translate(-50%, -50%)
   * para centralizar o conteúdo
- hero-center p tem max-width: 35em
   * na tela pequena fica bom, mas em tela grande o paragrafo fica para a esquerda e não alinhado com o resto do conteúdo que está alinhado no centro 
   * para resolver, só colocar uma margem automatica nos lados