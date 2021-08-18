# Conteúdo das aulas

**Requisitos**: Node.js, VSCode

**Plugins do VSCode**: editorconfig, gitlens, open in browser

## Aula 1

- HTML serve para estruturar a informação em uma página web
- HTML é composto por tags e elementos
- atributos fornecem informações de conteúdo e funcionamento das 
tags e elementos
- existem tags/elementos abertos e vazios
- essencialmente temos duas categorias de elementos: inline e block

## Aula 2

- ul, ol e dt sao elementos para criação de listas 
- svg é umformato para imagens vetoriais
- temos 3 formas de escrever css: inline (peso 3), internal (peso 2) e external (peso 1)
- É boa prática utilizar css em um arquivo externo para evitar as colisões de estilo
- padding é para dar espaçamento interno e externo do elemento
- margin é para dar espaço externo no elemento
- é possivel aplicar margem negativa porrem pading não
- box model é uma caixa que envolve todo elemento que consiste de margin border, padding, altura e largura
- a propriedade `box-sizing: border-box` faz cm uqe o padding e  borda não sejam somados com a largura e altura do elemento

- * é o seletor global

## Aula 3

- Utilizamos `%` porcentagem como unidade de medida para trabalhar com layout fluido
- para centralizar um elemento horizontalmente utilizamos a `margin` com o valor `auto` e o `widht` definido
- A propriedade `background`nos permite manusear o background de um elemento
- Por padrão o background-repeat vem com o valor `repeat` que repete o background que a gente colocar 
- a propriedade `background-size: cover` faz com quea imagem se ajuste ao elemento a fim de evitar distorsões 
- so utilize letras maiusculas no html caso necessário, por exemplo em siglas 

- utilizamos `%` como unidade de medida para trabalhar com layout fluido
- para centralizar um elemento horizontalmente utilizamos a `margin` com o 
valor `auto` e o `width` definido
- a propriedade `background` nos permite manusear o background de um elemento
- um elemento pode conter múltiplos backgrounds
- por padrão o `background-repeat` vem com o valor `repeat`
- a propriedade `background-size: cover` faz com que o imagem se ajuste ao 
elemento afim de evitar distorções
- para criar um efeito de overlay podemos utilizar o 
`background-image: linear-gradient(rgba(119, 98, 178, 0.6), rgba(119, 98, 178, 0.6))`
- podemos importar fonts através da tag `<link>`, `@import` ou `@font-face`
- várias propriedades do CSS são passadas de elemento pai para o filho, por exemplo `font-family`
- `letter-spacing` aplica espaçamento entre as letras de um texto
- utilize `text-transform: uppercase` para deixar texto em maiúsculo
- só utilize letras maiúsculas no HTML caso realmente necessário, por exemplo em siglas

## Aula 4

- classes no css possibilita o reaproveitamento de estilos 
- a propriedade list-style: none remove os pontos da lista
- o display inline-block permite que elementos sejam arranjados lado a lado
- o atributo target blank permite abrir o link em nova aba
- ao remover o outline é boa pratica prover alguma forma de enfatizar a interação do usuario com dado elemento
- pseudoclasse nos permite aplicar um estilo a um elemento sobre um estado especial, por exemplo hover, focus, first-child, visited, checked
- transition nos permite criar animações de transição nos valores das propriedades