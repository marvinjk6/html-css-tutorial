# Typography

- properties
- font-stack, generic family
- google fonts

## font-stack, generic fonts

Quando o browser não conseguir interpretar uma fonte constumizada definida é possivel passar os valores genéricos serão mostrados caso isso aconteça
- serif
- sans-serif
- cursive
- fantasy
- monospace

## Google fonts

O google fonts possue uma grande variedade de fontes que podem ser usada para os projetos
- quanto mais fontes externas, menos performance para a aplicação pois o broser vai buscar essas fontes externas
- é possivel importar pelo html ou pelo css
- é importante colocar antes do estilo quando for importar pelo html

## System fonts

Uma opção que está cada vez mais popular é usar as fontes do sistema que já estão instaladas nos dispositivos dos usuários.
Vantagens:
- carregamento da página mais rápido
- menos dores de cabeça
- o projeto vai ficar com uma aparência diferente de um dispositivo para o outro

Alguns exemplos:
- "-apple-system, BlinkMacSystemFont - fontes do sistema de dispositivos da apple
- "Segou UI" - usada para o sistema windows
- "Roboto" - fonte do sistema do Android

Escrever no font-family system-ui e o VS Code vai sugerir a opção

## font-weigth, font-style

- font-style: estilo da fonte, normal, italico
- font-weigth: pode passar valores de 100 a 900 ou palavras, normal, lighter, bold
- está no arquivo 01-fonts

## text-align, text-indent

- text-aling: vai modificar o alinhamento do texto, esquerda, centro, direita
- text-indent: é usado para identar um parágrafo

## More text properties

- line-height: distancia entre as linhas, se for um número sem a unidade a altura da linha será o número * o tamanho da fonte
- letter spacing: espaço entre as letras
- word-spacing: espaço entre as palavras
- text-transform: modifica o texto para maíusculas, minúsculas
- text-decoration: vai adicionar alguma decoração para o texto, muito usado none para links

