# Background image

Ordem para shorthand
- background: url("./image.png") - ao invés de usar uma cor, uma imagem será usada como background
- background-position
- background-size
- background-repeat: por padrão as imagens se repete
- background-attachment
- linear-gradient + shorthand
- ColorZilla

## Background-repeat

- background-repeat: repeat;
   * valor padrão, repete as imagens
- background-repeat: no-repeat;
   * não repete
- background-repeat: repeat-x;
   * repete no eixo-x
- background-repeat: repeat-y;
   * repete no eixo-y
- background-repeat: space;
   * cria um espaço entre as imagens repetidas
- background-repeat: round;
   * estica a imagem pra cobrir todo o background, só repete a imagem se houver espaço

## Background-size

- background-size: cover;
   * o tamanho da imagem vai fazer diferença nessa propriedade quando o cover é usado, pois vai cobrir o espaço com o tamanho da imagem
   * se a imagem for muito pequena e o espaço para cobrir muito grande, a qualidade será péssima. Como na small.jpeg

- background-size: contain;
   * vai manter a proporção da imagem se adequando ao espaço disponível, mas não vai preencher tudo


## Background-position

- background-position: center;
- background-position: left;
- background-position: top;
- background-position: bottom;
- background-position: 50% 50%; 
   * passar porcentagem: from left - from top

## Background-attachment


- background-attachment: fixed;
- background-attachment: scroll; padrão

## Linear Gradients

O linear-gradient() permite utilizar mais de uma cor junta no background, fazendo uma transição de uma cor para outra
- é possivel controlar a direção da transição
   * o padrão é de cima para baixo
   * 1º argumento da função é a direção
   * degrees
   * to right, to bottom
- porcentagem: controlar o quão sólida é a cor até fazer a transição onde a cor vai ficando mais fraca

## Background Image Overlay

- Usar o linear-gradient() com rgba e opacidade combinado com a imagem, para deixar ela mais fraca e o que está escrito aparecer com mais facilidade. 
- linear-gradient vem em primeiro     
- background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url("./big.jpeg");

## Colorzilla

- colorzilla ultimate css gradient generator
- é uma ferramenta para criar gradientes

