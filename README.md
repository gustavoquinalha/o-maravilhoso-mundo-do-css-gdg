https://codepen.io/gustavoquinalha/full/YrgbPg/
O CSS tem o poder de fazer isso aqui:
Virar isso aqui:

Já ouvi muita gente falar:
- Ah CSS é facil
- Eu não preciso de CSS
- Eu uso bootstrap (O pior é quem não sabe usar)
- CSS não é linguagem de programação
- CSS não faz a diferença

É, realmente CSS é uma linguagem de marcação. Por esses motivos que temos sites tão horríveis e inacessíveis, é por isso que vários projetos e startups fodas não vão pra frente! Costumam focar apenas no plano de negócio e as informações necessárias e não mostram o que realmente o usuário quer, que é se sentir confortável no site.

É o CSS que faz u UI/UX funcionar, é ele quem faz a acessibilidade, então precisamos muito focar no CSS.
Um bom design mostra a qualidade do serviço, o usuário não vai entrar no seu site, inspecionar o elemento e ver o que você usa, como você faz, NÃO! Ele quer navegar em um site foda que resolva seus problemas.
Mas as vezes um bom design não causa tanta diferença, mas se ele for ruim, fará.

Eu tenho certeza que todo mundo aqui quando entra num site foda pensa “Nossa que site louco!” e ainda olha todas as páginas. Por que?
porquê o CSS era incrível. E assim eu provo que o CSS faz a diferença. Agora imagina se nós temos o Melhor CSS, o melhor JS, melhor JAVA, não interessa. PRECISA SER O MELHOR. O resultado vai ser simplesmente o melhor.
O seu back-end só vai fazer a diferença se seu front-end for realmente bom! O seu front-end só vai fazer a diferença se seu back-end for realmente bom!

Um completa o outro, é tipo Yin Yang. Ou melhor, é igual as esferas do dragão, não faz diferença se você não tiver todas.


O fácil é o melhor! 
Desse jeito voce só se limita, e acaba deixando de lado os desafios mais legais, por que fazer um site ou sistema é muito legal(para mim é, e todos deveriam pensar assim, senão pense em trocar de emprego). A pessoa que escreve o JS e o CSS ou qualquer outra linguagem, tem que ter vontade pra programar, falar:
PORRA QUE TESÃO DE PROGRAMAR ESSA PORRA!

# O melhor do CSS

- Flexbox
- Grid Layout
- Animações (Keyframes, Transforms e Transitions)
- SVG
- Estilização(Shadows, gradients, borders)
- O resto

Eu parei para pensar quais as melhores features do CSS e acredito que essas são as melhores, pelo menos para mim. CSS é muito mais que so alinhar e colorir uma div
margin: 20px;
padding: 10px;
background: red
e ta pronto, NÃOOOOOO!

# Como realmente é:
- Lógica
- Planejamento (Ui/Ux, Styleguide ❤)
- Performance!important
- Detalhes fazem a diferença
- Bom senso
- Redundância

## Flexbox
Se você é front e ainda não manja flexbox, mano você ta moscando! No final do texto tem vários links maneiros, APROVEITE!
Ao mesmo tempo que é simples e fácil, é muito complexo e resolve todos os problemas. Torna todo layout simples de codificar e você consegue usa-lo em qualquer lugar.

This module introduces a new layout mode, flex layout, which is designed for laying out more complex applications and webpages.

Flexbox layout is most appropriate to the components of an application, and small-scale layouts, while the Grid layout is intended for larger scale layouts.

O flexbox é baseado em container e item, pai e filho.
O pai é responsável pelo comportamento dos filhos.
Pelo pai nós definimos como o flexbox vai se comportar, e nele aonde vão as propriedades de alinhamento.
Mas alguns filhos são rebeldes e possuem a propriedade align-self. Que torna o comportamento independente do pai.

O Main Axis é manuseado pelo justify-content
e Cross Axis é manuseado pelo align-items.

## Propriedades do container(Pai):
Display: flex | inline-flex
Flex-direction: row | row-reverse | column | column-reverse
Flex-wrap: nowrap | wrap | wrap-reverse
Justify-content: flex-start | flex-end | center | space-between | space-around
Align-items: flex-start | flex-end | center | baseline | stretch
Align-content: flex-start | flex-end | center | space-between | space-around | stretch

## Propriedades do item(Filho):
Order: integer
Flex-grow: number
Flex-shrink: number
Flex-basis: length | auto (px, %, rem…)
Align-self: auto | flex-start | flex-end | center | baseline | stretch

# Grid Layout

# Animações (Keyframes, Transforms e Transitions)

# SVG

# Estilização(Shadows, gradients, borders)
Ao invés de usarmos imagens mega pesadas com bordas redondas com gradientes e etc, conseguimos criar penas com CSS, sim é  possível, experimente.

# O resto

# Surpresa
???????

### Links flexbox:
https://www.w3.org/TR/css-flexbox-1/
https://tympanus.net/codrops/css_reference/flexbox/
https://facebook.github.io/react-native/docs/flexbox.html
https://hackernoon.com/11-things-i-learned-reading-the-flexbox-spec-5f0c799c776b
https://medium.freecodecamp.org/even-more-about-how-flexbox-works-explained-in-big-colorful-animated-gifs-a5a74812b053
https://pt.slideshare.net/rachelandrew/flexbox-and-grid-layout
https://youtu.be/_98SE8WUvLk
https://youtu.be/udV_GD5QNsI

### Links grid layout:
https://css-tricks.com/snippets/css/complete-guide-grid/
https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Grid_Layout
https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout
https://codepen.io/simoneas02/post/grid-layout
https://tympanus.net/codrops/css_reference/grid/
https://medium.com/@patrickbrosset/css-grid-layout-6c9cba6e8a5a

### Links Animações:
https://codepen.io/gustavoquinalha/
https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Animations/Usando_anima%C3%A7%C3%B5es_CSS
https://css-tricks.com/almanac/properties/a/animation/
https://codepen.io/willianjusten/pens/public/
https://www.w3schools.com/css/css3_animations.asp
https://daneden.github.io/animate.css/
http://mynameismatthieu.com/WOW/
http://pavlyukpetr.com/awesome/
https://robots.thoughtbot.com/css-animation-for-beginners
https://webdesign.tutsplus.com/articles/15-inspiring-examples-of-css-animation-on-codepen--cms-23937

### Links SVG:
https://github.com/willianjusten/awesome-svg
https://jakearchibald.com/2013/animated-line-drawing-svg/
https://vecta.io/app/edit/-KtwDC0qnA3wNPcd21Oh
https://designmodo.com/svg-patterns/
https://designmodo.com/svg-animation/
http://slides.com/sdrasner/svg-can-do-that
https://css-tricks.com/transparent-jpg-svg/
https://developer.mozilla.org/en-US/docs/Web/SVG/SVG_animation_with_SMIL
https://jakearchibald.github.io/svgomg/
https://kosamari.github.io/sbn/
