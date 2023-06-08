# CSS GRID

- usado para layouts bidimensionais

## Basicsyntax - grid-template-columns

Sempre que é preciso trabalhar com css grid é preciso
- 1 container pai
   * display: grid
   * grid-template-columns: propriedade que vai receber como valor o tamanho das colunas
- os elementos dentro desse container

## Implicit Grid

O grid é inteligente para que caso mais elementos sejam adicionados manter o layout colocado em grid-template-columns
- foi adicionado mais elementos no arquivo 01
- o tamanho e número de colunas foram respeitados
- o css grid adicionou os elementos criando linhas (é possível definir linhas também)

## units - auto

As unidade de medida são usadas tanto para colunas quanto para linhas (rows)
- px
- rem
- em
- % - responsivo
- auto - resposnsivo
- fr - responsivo - o mais usado

## grid-template-rows

Propriedade que vai estabelecer os valores das linhas do grid
- foi colocado height no container
- a terceira linha terá altura auto 

## fr - unit

fr - corresponde a fração do espaço disponível

## gap

É uma propriedade que vai dar um espaçamento entre os elementos
- grid-row-gap: obsoleto
- grid-column-gap: obsoleto
- grid-gap: obsoleto

Atualmente as propriedades usadas para o gap são
- row-gap
- column-gap
- gap: linha coluna

Quando o gap é usado e as colunas e linhas não estão como fração podem ocorrer problemas no layout, pois o espaço do gap é adicionado ao espaço dos elementos
- nesse caso seria necessário fazer cáculos
- apenas a fração será totalmente responsíva se encaixando no espaço disponível 

## Firefox developer tools

O developer tools do Firefox permite visualizar as linhas do grid, que é o próximo assunto, facilita a compreensão

## grid-lines

Quando o grid é criado ele vai possuir linhas:
- linhas nas colunas
- linhas nas linhas (row lines)
- é possível definir em qual linha determinado elemento começa e termina

Propriedades para definir onde o elemento começa e termina pela coluna
- grid-column-start: 1;
- grid-column-end: 3;
- shortcut - grid-column: start/end - 1/3;

Propriedades para definir onde o elemento começa e termina pela linha
- grid-row-start: 1;
- grid-row-end: 4;
- shortcut - grid-row: 1/4;

## Naming grid-lines

É possível nomear as linhas do grid
- olhar no arquivo 06

## grid-template-areas

Antes de tudo definir quantas colunas e linhas 
- Primeiro criar o grid-template-areas no container pai - colocando nomes e os lugares que esses nomes vão ocupar no template
- Depois com grid-area colocar nos elementos o nome que será atribuido ao elemento, definido no grid-template-areas

## order-property

- Todos os elementos possuem order: 0;
- quem ter o menor valor será mostrado primeiro e assim por diante

## repeat-function

- função para repetir valores
- repeat(qtd de vezes, valor repetido) - repeat(3, 1fr)
- exemmplo no arquivo 08-order-property

## justify-content

Muito similar ao flex-box, alinhamento horizontal
- se usar fração para o tamanho da coluna não irá funcionar

## align-content
 
- É preciso de uma altura definida no container para ser possível alinhar verticalmente
- stretch (default)

## align-items, jusitfy-items, align-self,justify-self

- align-items, jusitfy-items -> posiciona o conteudo do item
- align-self,justify-self -> posiciona o item selecionado

## minmax()

É uma função que pode ser usada com css grid, para determinar o tamanho máximo ou mínimo de uma coluna ou linha por exemplo
- primeiro argumento mínimo
- segundo máximo

## auto-fit / auto-fill

São propriedades que permitem configurar layouts com css-grid sem media queries
- basicamente o auto-fill sempre vai deixar espaço para mais elementos, caso de uso comum quando não se sabe a quantidade vinda no banco de dados
- auto-fit vai ocupar o espaço determinado 

Na próxima sessão terá exemplos de usos 


