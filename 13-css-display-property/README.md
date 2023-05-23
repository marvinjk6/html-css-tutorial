# Display property

- block: 
- inline:
- inline-block: é uma forma híbrida
- box-sizing: border-box

## Display property

Todos os elementos possuem a propriedade display por padrão
- block: sempre começam em uma nova linha e se expandem na largura completa da tela
   * O Browser vai considerer margin, padding, heigth, width, top, bottom
      * div
      * p
      * h1
- inline: não começam em uma nova linha, se expande na largura de seu conteúdo
   * O Browser NÃO vai considerar margin, heigth, width, top, bottom
      * img
      * a
      * span

## Basic Horizontal Centering

- Uma opção para centralizar um elemento com diplay block é usar margin: 0 auto; mas o elemento precisa ter width definido, se não ocupará a largura da tela
- e para texto usar o text-align: center;

## Mobile Navbar Example

- É muito comum usar listas com links para fazer os menus de navegação,
- O display block no link que está em uma lista é muito usado para fazer menu de navegação vertical, é preciso definir width

- Mas é possível usar outras abordagem, usando margem em li, colocando o padding em a


## Box-sizing: border-box

- box-sizing: content-box é o valor padrão
- box-sizing: border-box vai fazer com que o width do elemento seja respeitado,  se adicionar padding nesse elemento o tamanho ele não vai ser alterado pelo padding
- olhar no DevTools os elementos para ver o comportamento
- vantagem do box-sizing é que permite mais previsibilidade para o layout da página

## Display inline-block

Tipo híbrido
- não começa um nova linha
- Browser respeita margin, width, height
- uso muito comum é para fazer um menu de navegação horizontal

## Display:none, Opacity, Visibility

- display: none - remove o elemento do fluxo do documento
- opcacity: 0, visibility: hidden - preservam o espaço que o elemento está mas sem mostrar esse elemento
   * olhar no DevTools, esses elementos terão seus espaços preservados