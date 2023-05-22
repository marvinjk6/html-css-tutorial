# CSS Tutorial

Anotações importantes sobre css

## CSS Inline, internal, external

O CSS pode ser aplicado de 3 maneiras, inline, interno, externo. Em projetos é usado o modo externo para separar o código e tudo ficar mais organizado

## Power struggle

- Em relação a qual maneira é mais "forte", ou seja se um mesmo elemento for modificado das três maneira (interno, externo e inline) pelas mesmas propriedades o estilo que vai permanecer é o inline, depois o interno, por último o externo.
- Se um elemento possuir mais de um estilo prevalece o que foi escrito por último


## Basic CSS syntax

- selector: #-id, .-class, h1, table, p, etc...
- declaration block: {  }
- properties: background-color, color, font-size,
- value: blue, red, 16px

## Element selector

Seleciona pelos elementos do html, por exemplo h1, h2, p, div


## Id, classes

- o id precisa ser único para cada elemento - #id
- a classe pode ser usada para vários elementos - .class

## Div and span elements - HTML

Tanto a div como o span são usados parar agrupar elementos
- div: usada para agrupar multiplos elementos
- span: usado para agrupar conteúdo de forma inline
- é possível adicionar classes e ids para a div e span

## Inheritance in CSS

Basicamente um elemento vai herdar o estilo do pai, a menos que esse elemento tenha o seu próprio estilo
- se o elemento pai possuir cor, fonte, background-color o filho vai herdar essas propriedades, para alterar é só selecionar o elemento e modificar as propriedades assim sobrescrevendo as do elemento pai
- uma curiosidade é que algumas propriedades não são herdadas, como é o caso de border

## Last rule, Specifity and Universal Selector

Last rule:
- se um elemento possuir mais de dois estilos no documento, o estilo que for aplicado por último será o mostrado 

Specifity:
- ordem para saber qual é mais específico - tag element < class < id
- se um elemento tiver classe e id que modificam a mesma propriedade o que for definido no id será aplicado pois o id é mais específico

Universal selector (*)
- vai aplicar para todos os elementos do documento o que for definido nesse seletor

Site:
- https://www.w3schools.com/css/css_specificity.asp

## Combine selectors - Descendant Selector
É possível combinar seletores para selecionar os elementos, um deles é o seletor descendente. Site:
- https://www.w3schools.com/css/css_combinators.asp