# standard padrões para estudo em HTML e CSS e JS

Como funciona o Display: inline-block no HTML?

A propriedade DISPLAY  é a que rege como  o navegador irá fazer a fluidex dos itens  na tela.
No caso da nossa DIV o proprio navegador adcionou uma propriedade na nossa DIV que foi o DISPLAY=BLOCK, agora cabe a nós fazermos um OVERWRITE da mesma.

o DISPLAY com o valor =BLOCK; irá ocupar a lagura total do ELEMENTO PAI de onde ele está inserido e próximo ELEMENTO será posicionado VERTICALMENTE apos este ELEMENTO, vai existir uma quebra de linha e o ELEMENTO seguinte vai aparecer abaixo do ELEMENTO ORIGINAL, não importando a lagura que este elemento tenha, ou seja INDEMPENDENTE da largura deste ELEMENTO tenha , o próximo ELEMENTO  vai aparecer abaixo do ELEMENTO PAI. a FLUIDEZ PADRÃO DO ELEMENTO valor BLOCK é VERTICAL. Ou seja de cima para baixo.

Nesta aula aprenderemos a dar um overwrite em nosso ELEMENTOS para aLteramos a fluidez e colocarmos eles HORIZONTALMENTE. 

Alteraremos os ELEMENTOS da DIV .left, .right, .center nesta aula.

Colocaremos a propriedade DISPLAY no nosso cod. e o que acontecerá com o DISPLAY que o navegador colocou? Iremos fazer o que chamamos de OVERWRITE ou seja reescrevermos o cod do NAVEGADOR e passará valer o nosso. Ou seja a nossa informação de CSS sempre virá depois da informação do CSS que navegador.

no DISPLAY temos as propriedades:

DISPLAY=BLOCK; fluidex vertical é o padrão.

DISPLAY=INLINE; fluidex horizontal, para alteração de TEXTOS.

DISPLAY=INLINE-BLOCK fluidex horizontal, para alteração de BLOCOS. Quer dizer: Existe um ELEMENTO que é um BLOCO que será definido a WIDTH e HEIGHT que nos já definimos. Ele fluirá como se fosse um texto. Ou seja ele ficará INLINE não somente o TEXTO dentro do ELEMENTO mas TB o BLOCO. O mesmo irá ficar alinhado pelo BAIXO, caso haja Diferênça de autura , a diferênça ficará aparente na parte de  cima.



