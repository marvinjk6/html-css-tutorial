# Box Model

- padding: cria espaço entre o conteúdo e a sua borda, expandindo o elemento
- margin: cria espaço entre um elemento e outro
- border: borda do elemento, ela aumenta o espaço do elemento
- border-radius: arredondamento da borda
- negative margin: quando passar um valor negativo vai ter o efeito contrário de margin
   * no exemplo que eu fiz, a div blue fica por cima de green pois o margin top de square é sobrescrito, é como se o 60px de square não existisse então a margem negativa vai começar com a posição inicial de blue que seria colada em green
- outline: é uma borda que está fora do elemento, vem depois da borda
  * o legal do outline é o outline-offset que ao passar valores negativos vai para dentro do elemento e positivo para fora

## Border hack

As vezes alguns problemas de layout podem surgir, uma forma de visualizar onde o elemonto começa e termina é colocando uma borda em todos os elementos usado o seletor universal.