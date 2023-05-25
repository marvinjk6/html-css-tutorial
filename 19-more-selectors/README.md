# More selectors

- basic selectors
- pseudo class selectors
- pseudo element selector

## basic selectors

- id (#)
- class (.)
- universal (*)
- elemento (h1, p, div, button)

## descendant and child selectors

- #menu h1 - todos os h1 que estiverem dentro de #menu
- #meni > h1 - apenas os h1 que forem filhos direto de #menu

## ::first-line, ::first-letter pseudo elements

- ::first-line - seleciona a primeira linha 
- ::first-letter - seleciona a primeira letra

## :hover pseudo class selector

Uma pseudoclasse é usada para definir um estado especial de um elemento.

Por exemplo, pode ser usado para:

- Estilizar um elemento quando um usuário passa o mouse sobre ele (:hover)
- Estilizar links visitados e não visitados de forma diferente
- Estilizar um elemento quando ele recebe o foco

## links pseudo class selectors

Os links possuem pseudo classes específicas
- :link - não visitado
- :visited - visitado
- :hover - hover
- :active - quando o usuário está clicando

## :root pseudo-class Selector

- seleciona root element, o html, possui a maior especificidade
- css variaveis 
