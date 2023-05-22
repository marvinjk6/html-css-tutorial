# Units

- absolute, relative
- pixels
- em, rem
- vw, vh
- font-size, height, width

## Pixels

- undidade absoluta, um pontinho de tela
- font-size: tamanho da fonte
- height: altura de um elemento
- width: largura de um elemento

## Percent - units

- unidade relativa, relativa ao elemento pai
- ao mudar o tamanho do elemento pai o filho também irá mudar de acordo com a porcentagem definida

## Em - units

- unidade relativa, depende do elemento pai
- 1em = 16px valor padrão do browser
- 2em = 32px
- 2.5em = 24px
- Se o elemento pai ter 10px: 
   * 2em = valor base (10px) * número (2) = 20px
   * 1.3em = valor base (10px) * número (1.3) = 13px
   
## Rem - units

- unidade relativa, depende de root
- 1rem = valor base (16px) * número (1) = 16px
- valor padrão 16px
- é referente ao elemento html, então se no documento for alterado o valor do html, o rem vai ser relacionado a esse valor alterado
- é possível também alterar esse valor nas configurações do browser, mas isso vai depender do usuário

## Viewport Units - vh and vw

- unidade relativa, depende do tamanho da tela
- vh - viewport height - porcentagem da tela - 50vh
- vw - viewport width - porcentagem da tela - 75vw

## Default browser styles and Chrome DevTools

- Todos os elementos possuem um valores padrões que o browser dá ele
Chorme DevTools
- botão direito - inspecionar - Elementos
- é possível fazer testes com o DevTools

## Calc Function

Permite fazer operações matemáticas
- no exemplo da aula navbar possue 200px de altura, e banner possue 100 vh, isso faz com que a tela tenha mais do que 100% de altura, pois soma 100vh + 200px de altura de navbar
- é possível usar a funcão calc para fazer a subtração do banner - navbar deixando assim com o tamanho da tela

## min-height, max-height, overflow

- Quando a altura de um elemento não é passada, a altura será de acordo com conteúdo do elemento (auto)
- Em alguns casos quando a altura e largura é definida e a div possue muito contéudo, esse contéudo acaba saindo do espaço definido verticalmente
   * é posivel usar um propriedade chamada overflow para ajustar esse conteúdo que passou da altura definida
- min-height: define um valor de altura mínimo
- max-height: define um valor de altura máximo
   * são usados para responsividade
