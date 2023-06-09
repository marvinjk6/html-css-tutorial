# Grid Mini Projects

É um projeto que foi dividido em mini-projetos para trabalhar com grid

## Navbar
HTML 
- está em index.html

CSS
- em ul será aplicado o display grid, pois é o container onde estão os items (links)

## Cards

O layout de três colunas foi feito de duas maneiras
- 1ª usando media queries
- 2ª sem media queries, apenas com auto-fill ou auto-fit e minmax function
   * nessa abordagem é necessário usar um pouco de matemática
   * layout 3 colunas
      * calcular o gap 2rem=64px -> (1170 - 64px) = 1106 / 3 = 368.66 
   * layout 4 colunas
      * calcular gap 3rem=96px -> (1170 - 96) = 1074 / 4 = 268.5
   * lembrando que o auto-fill "deixa o espaço para outros elementos"

## Cards CSS - Row Height

foi colocado mais conteúdo no paragrafo do primeiro card, e o layout dos outros cards foram danificados, para corrigir
- em .card definido os tamanhos das linhas
   * imagem tamanho - auto
   * .card-info tamanho - 1fr - para garantir que caso tenho mais texto no parágrafo o tamanho será expandido
   * .card-footer tamanho - auto
