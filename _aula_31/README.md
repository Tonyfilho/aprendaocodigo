# standard padrões para estudo em HTML e CSS e JS

Aula 31 Iniciando um novo website - primeiros passos. Daremos divições ao nosso SITE, com valores SEMÂTICOS, usando elementos especificos de cada DIVISÃO.

Criamos na aula anterior um elemento SECTION e  uma classe no HTML chamada de "CHAMADA" para pormos nossa imagem ESTATICA do nosso trailer.

Esta seção criada , tem ocupar toda a janela do nosso site, iremos somente definir .

antes de pormos a imagem, vamos ver e inspecionar como aparece nossa SECTION dentro do nosso site. Podemos ver que : Aqui  no navegador não vemos nada, mas quando inspecionamos ela aparece, mas sem definições, pois não colocamos HEIGHT e WIDTH.

 1º height: 100vh; /*Definiremos um VH uma ALTURA de 100% do nosso VIEW RATE, ou seja 100% da tela vista por nosso olhos. Mas ficou uma margem que FOI ZERADA POR NOSSO CSS NORMALIZE. Caso n usassemos o NORMALIZE teriamos que zera-la lá no BODY colocando MARGIN=0px;. 

 2º width:  não  DEFINIREMOS  o WIDTH pois ele será definido AUTOMATICAMENTE pelo navegador 

 3º Usaremos um BACKGROUD: URL, onde apontaremos o site onde iremos usar a imagem de fundo, assim não precisaremos trazer a imagem para pasta do site.
 Todo o video hospedado ho youtube tem um ID exlusiva, com isto podemos VER esta ID no final do caminho da pagina do navegador, é o letras e numeros depois com/ que aparece no fim da pagina.
    EX "https://youtu.be/GvbzrqD_kno"
 Outro lugar onde vemos a ID é quando compartilhamos na opção "COMPARTILHAMENTO".
 Quando clico em compartilhar , ele dá o endereço e o final do endereço é o ID do video.
 com este link, podemos fazer varias coisa, uma delas e buscar a IMAGEM padrão do trailer usando ELEMENTOS NO CSS.

 E usaremos este caminho no BACKGROUD: URL"https://img.youtube.com/vi/GvbzrqD_kno/maxresdefault.jpg" Onde só substituimos o COD do video,  caso  queiramos mudar de foto.

 Temos que por uma IMAGEM que acompanha o tamanho , mesmo que tenhamos que diminir a pagina, isto se chama "PAGINAS RESPONSIVAS" ou seja sem ela REPEDIR e sem ela QUEBRAR.
Para isto temos que alterarmos algumas coisa no nosso BACKGROUND

3º BACKGROUND-POSITION:CENTER; O background-position: center center; Centralizaremos a nossa imagem na ALTURA E LARGURA, ele vai centralizar na largura e altura 

4º BACKGROUND-REPEAT:NO-REPEAT; O  background-repeat: no-repeat; Com isto acabamos com as repetições .

5º BACKGROUND-SIZE: 100% 100%;  /*faz com que a imagem cubra todo backgroud 100% do TOP/BOTTOM e  100%  do LEFT/RIGHT*/

6º BACKGROUND-ATTACHMENT: FIXED;  background-attachment: fixed;  fixamos a imagem no fundo do site, ou seja quando dermos um SCROW com mouse a IMAGEM ficará parada e o site 


Para finalizar, usaremos um efeito de escurecer a imagem para darmos uma visualização melhor dos nosso textos que ficarão sobre a imagem. Não faremos isto na Maquina, pois a imagem se encontra na NUVEM, então teremos que usar as propriedades do CSS para fazermos isto. É isto que faremos na próxima aula.








            

