# Flexbox

- no arquivo style os estilos das caixas serão aplicados
- as propriedades do flexbox ficarão nos arquivos html

## Naming convention

A convenção é:
- um container pai - flex-container
- containers filhos - flex-items

display:
- display: flex -> o container se comporta como um elemento block
- display: inline-flex -> o container se comporta como um elemento inline

## Flex-direction

É uma propriedade que afetará o comportamento do container - que contém display: flex;

- flex-direction:  row (default) | row-reverse | colunm | colunm-reverse
- row: elementos ficarão em linha, um do lado do outro
- column: elementos ficarão em coluna, um em baixo do outro

## Flex-wrap

É uma propriedade que afetará o comportamento do container

- wrap faz con que o layout se adapte a tela, se não houver espaço os elementos irão para linha de baixo
   * é o valor que provavelmente será mais usado
- nowrap é o comportamento padrão, se não houver espaço na tela os elementos não irão aparecer

## Justify-content

É uma propriedade que afetará as posições de todos os items

- Alinhamento horizontal
- flex-start: default
- evenly: distribuido igualmente

## Align-items

É uma propriedade que afetará as posições de todos os items

- Alinhamento vertical
- Para essa funcionalidade funcionar é preciso de height definido para o container que os elementos estão
- <strong>baseline</strong>
   * é similar ao flex-start, a diferença é que o baseline faz com que os elementos fiquem alinhados de acordo com o conteúdo, e não com o container
  start
   * foi colocada font-size maior para .box-3 para ver esse comportamento
   * um uso comum é no menu de navegação, geralmente a logo é maior que os links, para ficar alinhado com tamanho da logo o baseline é usado

## Align-content

É uma propriedade que afetará as posições de todos os items

- se preocupa com o alinhamento se exestirem multiplas linhas

## Main Axis | Cross Axis

- olhar a imagem
- Main Axis e Cross Axis mudam de acordo com o flex-direction

## Order property

Essa propriedade permite mudar a ordem dos elementos sem mexer no html
- por padrão o valor é 0
- quem ter o menor valor será o primeiro, se 2 terem o mesmo valor será respeitado a ordem do html

## Align-self

Essa propriedade permite posicionar um elemento específico
- possui os mesmos valores de align-items

## Flex-grow

Permite preencher o espaço de container
- valor default 0 para os elementos do container
- é possível passar essa propriedade para todos os elementos -> .box {flex-grow: 1}
   * eles vão aumentar de tamanho igualmente para preencher o container
- é possível selecionar um elemento específico
- quanto maior o valor mais espço do container o elemento ocupa

## Flex-shrink 

Essa propriedade basicamente diz se um elemento pode ou não diminuir de tamanho
- valor padrão: 1 - sim / 0 - não
- supondo que um elemento tenha 300px, quando a tela diminuísse ele iria diminuir pois o valor padrão é 1
- para que o elemento não diminua colocar 0 como valor de flex-shrink

## Flex-basis and flex

Flex-basis define um tamanho mínimo para os elementos do container
- caso possua padding, será acrecentado, a menos que box-sinzing: border-box
- para layouts não é aconselhavel usar padding para os lados nos elementos
- o aconselhavel é usar porcentagens em flex-basis 
   * caso queira margin usar cal(flex-basis% - (margem desejada))
   * ex: flex: 0 0 calc(25% - 1rem);

Shortcut para flex: flex-grow, flex-shrink, flex-basis

## New features

A propriedade mostrada é o gap <br>

Gap é uma propriedade que cria distancia entre os elementos
- podem ser em px, em, rem
- gap: (distacia linha) (distancia coluna)

