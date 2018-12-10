# standard padrões para estudo em HTML e CSS e JS

Como funciona o Display: Flex no HTML? A grande vantagem do DISPLAY:FLEX é que um ELEMENTO se comportará como ELEMENTO, ou seja vai FLUIR e alinhar em relação ao seu elemento PAI, e  ele carrega uma serie específicas de propriedades do FLEX. Pemitindo um controle melhor de linhamento.


Na aula anter vimos como  usamos a propriedade DISPLAY=INLINE-BLOCK, para conseguirmos que nossos 3 blocos de informações (As DIVS left, center, right) viessem flutuar horizontalmente e usamos o VERTICAL-ALIGN=TOP; e o TEXT-ALIGN=LEFT; para fazermos fluir as caixas (DIVs) para TOPO e seus textos para ESQUERDA.
Então alinharmos VERTICALMENTE nos elementos pelo TOP e alinharmos HORIZONNTALMENTE  pelo elemento PAI é que no nosso caso a DIV#CORPO.

Lembrando que quando trabalhamos o DISPLAY=INLINE-BLOCK os elementos serão calculados e alinhados  como se fosse TEXTO e isto não é intuitivo pois uma DIV não é um texto. Então não é INTUITIVO usarmos estas propriedades.

Para resolvermos isto usando o paramentro DISPLAY:FLEX; exitem  outros paramentros que o DISPLAY:FLEX; já carrega com ele.

DISPLAY:FLEX; Faz com que os elementos Caixa que são s nossas DIVs left, center e right flutuem na HORIZONTAL.
O DISPLAY:FLEX; é a opção mais fácil para definimos fluidez na horizontal. Podemos ver a diferença comparando as aulas 12 com a aula 13, em que mostra que NÃO temos uam altura uniforme com  as Caixas na aula 12 CASO NÃO termos já definido isto MANUALMENTE dentro das DIVs left, center e right com sito temos estas questões lá na frente de veremos dar problemas em outro texto. O DISPLAY:FLEX; para termos isto automatico.

Removeremos os TEXT-ALIGN=CENTER da DIV#CORPO, além do DISPLAY:INLINE-BLOCK e O VERTICAL-ALIGN:TOP, e TB o SELETOR que fizemos para pegar tudo que tinhamos dentro da DIVS ".left, .right, .center > * "

Lembrando que nossa FUIDES começa sempre pelo nosso ELEMENTO PAI que no nosso caso NÃO SERIA BODY para não termos que influênciar em toda pagina. Por isto será melhor  usarmos outra DIV que no nosso caso será  a

A parti da  DIV#CONTEINER  que iremos fazer fluidex das nossas caixas (DIVS ".left, .right, .center ) viNculando uma ID ou uma CLASS na  DIV#CONTEINER

na aula 12 colocamos o DISPLAY=INLINE-BLOCK dentro das caixas (DIVS ".left, .right, .center ) para que se comporta-se como se fosse um texto. Agora na aula 13 colocamemos fora das DIVs mas  dentro do OBJET PAI que se chama  DIV#CONTEINER , com isto já veremos a diferença de alinhamento  HORIZONTAL, e tb já ficam ALINHADOS PELA ALTURA  da maior caixa.


Segue as Propriedades e paramentros  do FLEX:
DISPLAY:FLEX; Faz um ELEMENTO fuir HORIZONTALMENTE.

JUSTIFY-CONTENT: CENTER; Faz o alinhamento central dos FLEX, como se fosse text-align para textos.

JUSTIFY-CONTENT: FLEX-START; Faz o alinhamento do INICIO do  OBJETO PAI. É o PADRÂO.

FLEX-DIRECTION: ROW; Faz o elementos fluirem como LINHA , este é o PADRÃO. Ou seja á carrega assim.

FLEX-DIRECTION: ROW-REVERSE ; Faz a linha começar do lado reverso do OBJETO PAI, além de reverter a posição do ELEMENTO vinculados as caixas (Divs).

FLEX-DIRECTION: COLUMN; Faz o elementos fluirem como COLUNA.

FLEX-WRAP: NOWRAP; Sem quebra de LINHA, este é o PADRÂO. Caso a largura diminua.

FLEX-WRAP: WRAP; Com quebra de LINHA. Caso a largura diminua. Voltando a ser COLUNA.

ALIGN-ITEMS: STRETCH; Faz alinhar pelo maior e alonga os menores. Já é PADRÂO do FLEX.

ALIGN-ITEMS: CENTER; Faz as Colunas alinharem pelo TOPO maior caixa, e mater um alinhamento e distância  igual entre as CAIXAS na vertical.








