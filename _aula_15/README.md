# standard padrões para estudo em HTML e CSS e JS

Como funciona o Float no HTML (2a. parte)

No video anterior vimos como usar a propriedade do float para  modificar a propriedade de ALINHAMENTO e FLUIDES do elementos dentro do nosso documento HTML .

Na aula anterior  vimos que o nossos elementos  da "ESQUERDA E DA DIREITA" tem escapado do espaço que temos na nossa CAIXA com a ID#CONTEINER . Lembrando que nosso CONTEINER não tem margem em relação ao elemento PAI.

Inspecionando nosso  elemento pela aula 14, veremos que a nossa DIV centro tem a mesma ALTURA da DIV com a ID#CONTEINER, por isto que n/ temos a MARGEM q tinhamos ANTES na aula 13 com o FLEX.

Inspecionando nosso  elemento pela aula 14, vemos tb que as caixas esquerda e direita são maiores do que a caixa do centro, ou seja nosso conteiner tem a altura da caixa central e a da esquerda e direita são maiores.

Neste caso, nós podemos definir como  este elementos irão aparecer. Podemos definir se queremos que estes elementos apareçam completamente, ou parte dele, ou se mostraremos somente a parte visível deste elemento.

Podemos imaginar que nosso conteiner seja uma janela, em que somente podemos ver uma parte do conteudo. Podemos ter uma BARRA de ROLAGEM na lateral ou podemos dizer que a altura do elemento pai seja sulficiente para que as caixas caibam dentro. Para alterarmos isto usaremos uma PROPRIEDADE CHAMADA OVERFLOW.


OVERFLOW:HIDDEN; :/*  Faz com que fique escondido  diferença de tamanho das CAIXAS com isto AUMENTARÁ tamanho da caixa. Ele usará a referencia da MAIOR caixa. HIDDEN vai fazer os elementos caibam na altura DEFINIDA do elemento PAI. Caso n seja definida o NAVEGADOR automaticamente dinirá um altura SUFICIENTE para mostrar todos elementos  .  */

OVERFLOW:HIDDEN; Fará mais sentido se definimos uma altura para nosso CONTEINER

OVERFLOW:SCROW; Cria uma barra de rolagem para elementos .
OVERFLOW:AUTO; É uma auternacia entre a opção HIDDEN e SCROW, nomemente aparece somente o SCROW LATERAL.

Neste caso quando usamos FLOAT, temos que criar uma MARGEM esqueda para elemmento esquerdo e uma margem direita para elemento direito.

Mesmo Configurando e ficando próximo do FLEX, quando diminuimos ou usamos varios tamanhos de Pagina veremos os problemas que FLOAT acumula. Com isto veremos as DISTÂNCIAS configuradas do FLOAT se perderem. A medida dos texto primeiro e depois as caixas, assim que as paginas diminuem.

Quando formos trabalhar com designer e tamanho de tela, tipo celular de tablet e outros  veremos os problemas fo FLOAT.









