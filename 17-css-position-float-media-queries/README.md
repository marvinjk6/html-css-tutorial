# Float, Position, Media Queries, z-index, pseudo elements

- float
- position
- media-queries
- z-index
- ::before, ::after pseudo elements

## Float

- O elemento que conter a propriedade float vai sair do fluxo normal, e irá flutuar
- para limpar esse fluxo usar a propriedade clear

## Position static

É o posicionamento padrão dos elementos, após um elemento vem o outro

## Position relative

- A posição será relativa a posição normal do elemento 
- é possível posicionar o elemento usando top, bottom, left, right

## Position absolute

- Quando position abolute é usado a posição do elemento será relativa ao elemento pai com o position diferente de static
- se o elemento pai ou nenhum superior ter posicionamento relativo, o absolute será relativo ao body
- fazer o teste colocando posicionamento relativo para div e depois para classe two

## Position fixed

- O posicionamento será fixo com relação a viewport, mesmo quando ter o scroll e for abaixando o conteúdo será mostrado
- uso muito comum é com menus de navegação fixo na parte superior do janela 
- O elemento com posicionamento fiexed sai do fluxo comum, com o conteúdo que vem depois vai tomar o lugar de onde está o elemento com posicionamento fixo, seguindo a ordem do html

## Position sticky

- o posicionamento sticky deixa o elemento seguindo o fluxo normal do documento
- alterna o comportamento entre relativo e depois fixo quando a posição bate com a viewport ai o elemento gruda na tela

## Media queries

- Design responsivo
- Estilizar os elementos de acordo com o tamnho da tela
- min-width: começa com - vai ser aplicado quando chegar nesse tamanho mínimo
- max-width: até o tamanho determinado será aplicado, se passar perderá esse estilo
- é importante colocar em ordem
   * se for min-width, do menor tamnho para o maior
   * se for max-width, do maior para o menor
   * para não sobrescrever o estilo
- Mobile first: a ideia é fazer o site primeiro para o mobile e depois ir ajustando o layout para dispositivos maiores
- a sintaxe é muito importante para funcionar o media queries
- apenas as propriedades que estão no media queires serão modificadas, o que não terá o estilo definido no css

## z-index

- o z-index altera qual elemento está na frente do outro para aparecer primero
- quanto maior o z-index primeiro o elemento aparecerá
- por padrão todos os valores do z-index é 0
- aceita valores negativos
- o z-index não funciona para posicionamento static

## Pseudo Elements ::before, ::after

- Cria um elemento e insere antes ou depois do conteúdo do elemento selecionado
- Não funciona com img
- a propriedade content é obrigatória para funcionar

## ::before and ::after Example

- img não funciona esses pseudo elementos
- foi colocado na div
   * para o conteudo aparecer é preciso de width e heigth pois content está vazio ""
   * o objetivo é colocar bordas

## Inset property -  cobrindo elemento com position absolute

- a propriedade insety é um shorthand que corresponde a top, right, left bottom propriedades 
- A ideia dessa aula é cobrir um elemento com o position absolute, isso é util com o hover, para dar um efeito bacana
- o elemento pai com positon relative
- elemento filho com position absolute
- inset: 0; vai cobrir todo o elemento pai com o background do filho