# CSS tutorial continued

- Css variables
- Font awesome icons
- text-shadow, box-shadow
- Browser Prefixes
- Semantic HTML
- object-fit
- Emmet Snippets

## Css variavles

- As variaveis permitem armazenar valores e re-usar esses valores pelo projeto
- elas podem ser usadas para qualquer propriedade (color, line-heigth, transition)
- :root {} as variaveis que ficam dentro do pseudo elemento root são GLOBAIS, todos os elementos do projeto possuem acesso
- é ppossível definir variáveis locais (em main), quem estiver dentro dessa div podem usar a variavel

## FontAwesome Icons

Um site incrivel para encontrar icones para usar nos projetos
- opções para usar:
   * Baixar no computador:
      - Docs
      - Web
      - Host Yourself - web fonts
      - Download the Font Awesome v6 files 
      - linkar o html com os ícones - all.css ou all.min.css
   * usar de uma fonte externa:
      - ir no site do: https://cdnjs.com/
      - procurar por fontwesome

## FontAwesome Icons - SVG Approach

No próprio site do fontawesome escolhendo o link aparece a opção SVG

## Text-shadow - box-shadow

- text-shadow - eixoX - eixoY - blur - cor
- mesma coisa para o box-shadow
- css text-shadow generator
- css box-shadow genertor

## Browser Prefixes

- https://caniuse.com/ - site para saber para quais propriedades os browsers já estão reconhecendo
- https://shouldiprefix.com/ - site que mostra quais propriedades precisam de prefixos
- Uma opção é instalar uma extensão do VS code que coloca os prefixos, existem pacotes do npm que também fazer 

## Semantic HTML

- São elementos que possuem um significado, eles servem para acessibilidade, posicionamento nos mecanismos de busca
- https://www.w3schools.com/html/html5_semantic_elements.asp

## object-fit

- propriedade que permite redimensionar img e video elementos para se encaixar em seus containers, sem estragar a imagem
- é similar com background-size
- object-fit: cover, contain, fill, none, scale-down

## Emmet workflow

O VSCode já possui o emmet quando ele é baixado, alguns exemplos:

- h1.header.light 
- button#btn.btn-dark
- ul>li*5>a.link
- p{Esse é um parágrafo}
- ul>li*5{número $}

site: https://emmet.io/

## :is()

- Essa pseudo classe recebe como argumento seletores, e seleciona qualquer elemento que esteja dentro desses seletores
- a intenção é escrever menos código

## :not()

- Similar ao :is(), mas vai selecionar a propriedade que não está nos seletores escolhidos como argumentos da função

## HSL Color Values

HSL significa matriz, saturação e luminosidade.
<br>

Valores HSL:
- hsl(matriz, saturação, luminosidade).

Matriz é um valor em graus na roda de cores de 0 a 360.
- 0º é vermelho
- 60º amarelo
- 120º é verde
- 180º é cyan
- 240º é azul
- 300º magenta

A saturação é um valor percentual:
- 0% significa um tom de cinza
- 100% é a cor completa.

A luminosidade também é um valor percentual:
- 0% é preto
- 100% é branco