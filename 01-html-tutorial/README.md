# HTML tutorial

Anotações sobre a seção

## Images
Algumas tags são únicas, como <'img'> e <'br' /> a barra no final é opcional, mas é importante usar em alguns momentos como no framework Reactjs
<br>

Alguns sites para encontrar imagens grátis para usar em projetos:
- unsplash
- pexels
- pixabay
- gratisography - possue imagens engraçadas também

Algumas imagens possuem um tamanho muito grande e apesar de ser possível diminuir o tamanho e altura no browser a imagem continua muito grande com relação a memória e isso prejudica a performance do site, algumas ferramentas:
- usar o paint 3D para diminuir a resolução da imagem
- TinyJPG
- Compressor
- Squoosh
- ReduceImages

## Links within a page

Para fazer a conexão de um link para um elemento que está no mesmo documento html, é preciso do id para fazer essa conexão, passar o id no atributo href=#id


## Empty links

Dentro das tags de link <'a'> é possivel passar textos, mas também outras tags, que serão transformadas em links:
- img
- h1
- icons

## Special Characters

São carateres que precisam de um valor diferente para ser mostrado no html.Site para encontrar caracteres especiais do html

site: https://www.w3schools.com/html/html_symbols.asp

## Forms 

Para coletar valores de um formulário apropriadamente o back-end precisa ser configurado corretamente, assim como o front-end, que vai mostrar na página os campos para serem preenchidos.
<br>

form atributos:
- action: específica para onde os dados do formulário serão enviados assim que o botão de submit é clicado
- method: qual será o método do protocolo http que será usado para enviar os dados, informações sensíveis sempre devem ser enviadas pelo método POST

input atributos:
- type: o tipo de input
- name: qual é o nome que será dado a esse input, é importante pois o back-end vai identificar qual é o input pelo name dele
- id: é importante para ser usado em conjunto com a tag label, o atributo for da label recebe o id do input

## Inputs

* radio:
  - name: o atributo name do input radio precisa ser igual para todos os input radio que são conectados, por exemplo no código os dois radio possuem o name gender, o que significa que um dos dois valores vai ser selecionado mas são referentes a uma mesma coisa que é o gênero da pessoa. Caso o name seja diferente é possível selecionar os dois
  - checked: o radio que estiver com checked já vai aparecer como selecionado
  - value: se refere ao valor mesmo que o back-end está esperando e que será enviado 

* checkbox:
  - os atributos funcionam da mesma maneira que o radio, a diferença é que apesar de terem o mesmo name é possível selecionar mais de um


## Keyboard Shortcuts

- undo - ctrl + z
- multiple cursor - segurar a tecla alt e ir clicando com o cursor
- alt + d - para mudar algo de lugar usando a setinha