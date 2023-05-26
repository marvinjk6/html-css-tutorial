# Transform, transtition, animation

- transform: translate(), rotate(), scale(), skew()
- transition: mudanças de estado (muda com o tempo)
- animation: mudança de destado (muda com o tempo com mais controle)

## Transform - translate()

Os valores para propriedade transform são funções
- a primeira será o translate()
- altera a posição de acordo com o eixo x-y
- aceitando como valores px, %, em. Se for porcentagem será em relação ao width e heigth do elemento
- translateX 
- translateY
- translate(x, y)

## Transform - scale()

O scale() aumenta o tamanho do elemento proporcionalmente, são passados unidades como valor
- scaleX(2) - dobro no eixo x
- scaleY(0.5) - diminui metade no eixo y
- scale(1.2, 1.5) - 1.2 eixo x - 1.5 eixo y
- scale(2) - dobra o tamanho nos dois eixos

## Transform - rotate()

O rotate() vai rotacionar o elemento, como valor são passado degrees (deg)
- rotateX e rotateY usados separadamente vão diminuindo o elemento até ele sumir. (não são usados separadamente)

## Transform - skew()

Eu não compreendi essa função, mas o valor é passado em (deg)

## Transition - property - duration

A transition permite controlar mudanças com o tempo
- um uso muito comum é com o estado hover
- transition-property: background - propriedade que terá transição
- transition-duration: 2s - duração da transição
- a div red e blue o hover é instantâneo, na green tem transição 

## Multiple transitions

- É possível adicionar mais de uma propriedade na transição, assim como uma duration diferente para essa segunda propriedade
- exemplo no arquivo 06-transition...

## Transition Delay - shorthand - all properties

- transition-delay - é um tempo que congela a transição antes dela acontecer
- shorthand - transition: property duration timing-function delay  - (timing-function delay são opcionais)

## Transition timing function

- Controla como a transição vai acontecer, se comportar
- valores para transition-timing-function:
   * ease - padrão
   * linear - mesma velocidade no começo e fim
   * ease-in - começa devagar
   * ease-out - termina devagar
   * ease-in-out - começa devagar, meio rápido, termina devagar

## Animation

- As animações dão mais opções para controle da animação
- As transições acontecem do ponto zero e vai pro final
- Nas animações é possível selecionar os ESTADOS com porcentagens
   * 50% - no meio da animação
   * 60% da animação

## Animation - fill mode

Se refere aos valores que são aplicados pela animação fora do tempo que ela esta sendo executada, quando a animação ja finalizou
- por exemplo a div no exemplo começa com opacidade 0 e no final ela terminaria com opacidade 0, pois é o comportamento padrão
- com o animation-fill-mode: fowards;  - mantém o estado final da animação colocado em 100%
   * a div não vai sumir pois no final da animação (100%) a opacidade é 1 e mantém esse estado
- com o animation-fill-mode: backwards; - mantém o estado inicial da animação (0%)
   * a div vai sumir pois a opacidade é 0


