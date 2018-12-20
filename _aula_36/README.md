# standard padrões para estudo em HTML e CSS e JS

Aula 36 Iniciando um novo website . Vimos a Aula anterior como usar uma imagem como fundo e como fazer uma transparencia da mesma.

Nesta Aula veremos como Usar POSITION e DISPLAY: FLEX para posicionar nossos elementos HTML (1a Parte) por o Barner sobre a imagem.

Neste video faremos a parte de cima do site, onde no nosso mockup


Direita: Logo do site
central : onde colocaremos o banner do site
Esquerda : Fotografia do Usuario, ou logo do facebook

Para trabalharmos este layout temos um elemento a DIREITA, UM NO CENTRO E OUTRO A ESQUERDA.     

se entrarmos no nosso HTML, vemos uma SECTION classe.CHAMADA e HEADER classe.AREA_CHAMADA  e  dentro temos os nossos H2.

Então antes dele, faremos um DIV, o por que não usamos um nome semântico? Por que isto é SEÇÂO do nosso site que fica dentro do HEADER que já semântico, ou seja é uma divisão dentro de uma classe semântica.

digitaremos assim usando o recurso do ERMMET:

.parte_superior +tab e ficará assim:
 <div class="parte_superior"></div>

 Aqui dentro criaremos nas 3 divisões.
 Podemos tb já ir no CSS e definirmos as config.desta classe.
 O que ja sabemos é: 
 1º Que a CAIXA OU DIV.parte_superior oculpa toda a largura do elemento background.
 
 ficando assim:


a DIV ficará alinhada e centralizada com ELEMENTO do fundo SECTION
.parte_superior { 
                width: 100vw; /*usaremos 100% do nosso RW ou ratewiew e nosso BANNER terá 720px */

                height: 90px; /*a altura será a mesma do BANNER*/

                display: flex; /*distribuiiremos nosso ELEMENTOS*/

                justify-content: center; /*Justificaremos o conteudo da nossa DIV centralizada na LARGURA */

                align-items: center; Alinharemos o conteudo da nossa DIV centralizada na ALTURA no centro da DIV 
                }
E dentro desta  DIV.parte_superior
OBS: Definimos o BANNER com 728px largura e 90 px de altura.
Dentro da nossa DIV CLASS.PARTE_SUPERIOR criaremos 3 outras DIVS a onde colocaremos nosso elementos:
        LOGO "esquerdo" aqui colocaremos uma imagem de logo:
           <div class="logo">
                <img src="_image/logo.png" alt="LogoTipo do Site">
           </div>

        Sendo que SRC é o caminho da IMAGEM
        SENDO que ALT é a descrição alternativa da imagem , que será usada quando a imagem não aparece no HTML. 

Fazendo somente isto e recarregando o nosso site, veremos que a IMAGEM passará ou sairá da DIV, e não é isto que queremos. Isto acontence por estamos usando o FLEX, ou seja o FEX diz: Quero que todas as  imagens fiquem centralizadas na minha DIV.

Para resolver isto, temos que configurar os elementos da CLASS.LOGO que aqui seria o TAMANHO da nossa imagem: 

        
.logo > img {  " > MAIOR " que dizer "TUDO que tiver dentro ou pertencer" ao IMG 
         width: 250px; dests forma a imagem ficará com 250PX.
}
 Conf. um MARGEN lá no elemento PAI , para baixar nossa imagem. 




                   BANNER "centro"

Configuraremos nosso 2º ELEMENTO que é o BANNER, faremos da mesma forma criando uma DIV.banner_superior:
          <div class="banner_superior">
                <img src="_image/banner_alto.jpeg" alt="Banner Superior do Site">
         </div>
Só fazendo isto, veremos nosso ELEMENTOS JUNTOS e CENTRALIZADOS

                 LOGO_FACEBOOK "direito"
Iremos fazer a 3ª DIV tb usando uma imagem, e podemos pegar esta imagem direto do facebook pela pagina: 
               https://pt-pt.facebookbrand.com/

Podemos entrar aqui e escolhe a Midia que queremos, o tipo de Logo, navege e veja as opções. Iremos usar a opção ONLINE








