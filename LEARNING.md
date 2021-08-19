# Conteúdo das aulas
**Requisitos**: Node.js, VSCode
**Plugins do VSCode**: editorconfig, gitlens, open in browser, SVG preview
## Aula 1
- HTML serve para estruturar a informação em uma página web
- HTML é composto por tags e elementos
- atributos fornecem informações de conteúdo e funcionamento das
tags e elementos
- existem tags/elementos abertos e vazios
- essencialmente temos duas categorias de elementos: inline e block
## Aula 2
- ul, ol e dt são elementos para criação de listas
- svg é um formato de imagem para imagens vetoriais
- temos 3 formas de escrever CSS: inline(peso 3), internal(peso 2), external(peso1)
- é boa prática sempre utilizar CSS em um arquivo externo para evitar colisões de estilo
- padding é para dar espaçamento interno em um elemento
- margin é para dar espaçamento externo em um elemento
- é possível aplicar margin negativa, porém padding não
- box-model é uma caixa que envolve todo elemento e consiste de `margin`, `border`,
`padding`, `height` e `width`
- a propriedade `box-sizing: border-box` faz com que o padding e a borda não
sejam somados com a largura e altura do elemento
- `*` é o seletor global
## Aula 3
- utilizamos `%` como unidade de medida para trabalhar com layout fluido
- para centralizar um elemento horizontalmente utilizamos a 'margin' com o
valor `auto` e o `width` definido
- a propriedade `background` nos permite manusear o background de um elemento
- um elemento pode conter múltiplos backgrounds
- por padrão o `background-repeat` vem com o valor `repeat`
- a propriedade `background-size: cover` faz com que a imagem se ajuste ao
elemento a fim de evitar distorções
- para criar um efeito de overlay podemos utilizar o
`background-image: linear-gradient(rgba(119, 98, 178, 0.6), rgba(119, 98, 178, 0.6)), url(caminho da imagem)`
- podemos importar `fonts` através da tag `<link>`, `@import` ou `@font-face`
- várias propriedades do CSS são passadas de elemento pai para o filho, por exemplo `font-family`
- `letter-spacing`aplica espaçamento entre as letras de um texto
- utilize `text-transform: uppercase` para deixar o texto em maiúsculo
- só utilize letras maiúsculas no HTML caso realmente necessário, por exemplo em siglas
## Aula 4
- classes no CSS possibilitam o reaproveitamento e isolamento de estilos
- a propriedade `list-style: none` remove os pontos da lista
- o `display: inline-block` permite que elementos sejam arranjados lado a lado
- o atributo `target="_blank"` no element `<a>` faz com que o link seja aberto
em uma aba nova
- ao remover o `outline` é boa prática prover alguma forma de enfatizar a interação
do usuário com dado elemento
- pseudo-classes nos permite aplicar um estilo a um elemento sobre um estado
especial, por exemplo: `:hover`, `:focus`, `:first-child`, `:visited`, `:checked` ...
- `transition` nos permite criar animações de alterações de valores das propriedades
- o flex-box layout provê um modo eficiente de dispor, alinhar e distribuir espaçamento
entre elementos que estão contidos em um container flex, indepentente das suas dimensões
- o flex-box é unidirecional, ou seja só conseguimos trabalhar em um dos eixos (x ou y)
por container
- a propriedade `flex-direction` possibilita declarar qual a direção dos
itens de um container flex
- os itens de um container flex são flexíveis e adaptam as suas dimensões para se
encaixarem no container
- para realizar a quebra de linha utilizamos a propriedade `flex-wrap: wrap` e
definimos a largura de cada elemento que estiver contido em um container flex
## Aula 5
- a unidade de medida `vh` é equivalente ao valor relativo à altura do viewport
- `align-items` permite trabalhar com alinhamento dos items na vertical contando
que o `flex-direction` seja `row`
- `justify-content` permite trabalhar com alinhamento e disposição da horizontal contando
que o `flex-direction` seja `row`
- `align-content` permite o alinhamento dos items em um container flex com `flex-wrap`
- o .editorconfig é um arquivo com configurações para o nosso code editor