# standard padrões para estudo em HTML e CSS e JS

RESUMO DAS AULAS 12 13 14 E 15 QUE FALA SOBRE: Display: Inline-block, Flex e Float

    na aula 12 colocamos o DISPLAY=INLINE-BLOCK dentro das caixas 

                   DISPLAY=INLINE-BLOCK, 
Os elementos (DAs DIVS left, center, right) passam a se comportar como se fosse texto. A relação deles e  como fluem dentro da caixa, da mesma forma que alinhamos eles como os outros elementos e com o elemento PAI usando ATRIBUTOS de texto são estes principais abaixo.
TEXT-ALIGN:
VERTICAL-ALIGN:
LINE-HEIGHT:

O DISPLAY=INLINE-BLOCK não alinhou a altura das caixas pela a altura da maior, que é o que o Flex faz por padrão.
O grande cuidado é lembrar que quando formos  usar DISPLAY=INLINE-BLOCK ele se comportará como se fosse TEXTO. O que é preciso sempre ver é: Se a formatação que estamos aplicando sobre o DISPLAY=INLINE-BLOCK não afete o texto que se encontra dentro do DISPLAY=INLINE-BLOCK. por isto é normal fazer um tipo de SELETOR em que podemos  reformata o texto interno  do DISPLAY=INLINE-BLOCK. 
EX.  onde o ">" sinal de maior fala que é para SELECIONAR INTERNAMENTE e o  "*" sinal de asterisco fala que TUDO que estiver DENTRO das caixas serão afetados.

.left, .right, .center > * {
    text-align: center;
}

                        o DISPLAY:FLEX;

Para resolvermos isto usando o paramentro DISPLAY:FLEX; exitem  outros paramentros que o DISPLAY:FLEX; já carrega com ele.

DISPLAY:FLEX; Faz com que os elementos Caixa que são s nossas DIVs left, center e right flutuem na HORIZONTAL.
O DISPLAY:FLEX; é a opção mais fácil para definimos fluidez na horizontal. 
 o DISPLAY:FLEX; já acerta o alinhamento AUTOMATICAMENTE e altura das caixas  e tb já ficam ALINHADOS PELA ALTURA  da maior caixa.
 Não foi necessário informarmos MARGENS ESQUERDA E DIREITA, a não ser as proprias margens da (Das DIVS left, center, right) onde temos o texto.
 A única  DESVANTAGEM DO FLEX  é que ele não funciona bem em SISTEMA OP com NAVEGADORES ANTIGOS. Tipo Win7, Win8 com navegadores antigos.
 Então precisaremos de um PLANO B, usando o JS para fazer o alinhamemto, mas veremos isto para frente.

 Qual a adif. entre o DISPLAY=INLINE-BLOCK e  o DISPLAY:FLEX;, no INLINE tivemos que por ele dentro das caixas FILHOs , e já o FLEX colocamos na caixa PAI chamanda de conteiner


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


                    O FLOAT 
O  Float não é um atributo para centralizar ELEMENTOS, é um atributo para retirar nosso elementos do FLUXO NORMAL e colocar entre TEXTOS a ESQUERDA E A DIREITA .

O motivo ao qual ele foi criado era para criarmos elementos que fluam entorno de TEXTO a ESQUERDA E A DIREITA ,  é o caso quando vemos uma foto de uma revista ou um texto envolvendo uma  imagem.
O Float  é muito utilizado para fazermos estes alinhamentos de texto e imagens, funciona muito bem em navegadores ANTIGOS. O Float faz a gente REPENSAR  o codigo quando formos usar TECNOLOGIAS MAIS NOVAS COMO SMARTFONE E TABLETS.

Um exemplo que podemos ver, é que para ternos os elementos left, center e right alinhados , tivemos que MUDAR a ordem deles no HTML,c olocando assim: left, right e center... com isto tiremos que  por o WIDTH da ESC. e DIR como AUTO. Por que no FLOAT o alinhamento não é pelo OBJETO PAI e sim pelo OBJETO anterior dele, que no nosso caso foi  o LEFT em relação do RIGHT.








