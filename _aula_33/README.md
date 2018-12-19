# standard padrões para estudo em HTML e CSS e JS

Aula 33 Iniciando um novo website . Vimos a Aula anterior como usar uma imagem como fundo e como fazer uma transparencia da mesma.

Nesta aula colocaremos os outros elementos sobre a imagem, segundo  o mockup da aula, temos um texto chamado "TRAILER EM DESTAQUE" que está centralizado, mas um pouco abaixo do meio do nosso brackground. Mas proximo da sessão onde colocaremos nosso cartazes dos nosso filmes.


1º Faremos nosso título em 2 linhas no HTML dentro da nossa SECTION, podemos usar o <h2> para quebrar.
usando nosso ERMMENT daremos o seguinte comando, já criando um classe chamanda AREA_CHAMADA, com um H2 com classe chamana TITULO , e outro H2 com classe chamanda SUBTITULO. Digitaremos assim e depois daremos o TAB.

header.area_chamada>h2.titulo+h2.subtitulo + TAB e ficará assim no seu HTML:
  <header class="area_chamada">
        <h2 class="titulo"></h2>
        <h2 class="subtitulo"></h2>
 </header>

2ª Passo é posicionar eles dentro da nossa pagina. Usaremos nosso elemento principal que é SECTION com classe CHAMADA, que já temos configurado. Dando um FLEX nele.

 display: flex; colocamos um display aqui, para configurar o HEADER dentro do nosso SECTION , mas somente ELE não mudará oq ue queremos , visto que  o FLEX por PADRÃO já configura para~a esquerda, por isto temos que usar outro atributo do FLEX.
 temos duas forma de fazer isto.

 Podemos fazer isto de 2 formas:
    1 usando:
    justify-content: center;
    align-items: center;

    2 Usando: Inspencionando o ELEMENTO podemover o resultado.
    Dentro da HEADER classe AREA_CHAMADA criarmos MARGENS AUTOMATICAs com isto todas as margens são iguais, o texto ficará centralizado para todos os lados .
    .area_chamada {
            text-align: center;
            margin: auto;
            margin-bottom: 180px;
}
Em nosso MOCKUP planajamos nosso um texto que não ficaria 100% centralizado, visto que queremos ele um pouco abaixo do CENTRO. Ou seja na largura ele está correto mas na altura não, podemos podemos mudar o MARGIN para ficar AUTO no LEFT/RIGHT  e configurar um TOP/BOTTOM com medidas .
              margin-bottom: 180px;

ou simplemente colocamos um valor no MARGIN-BOTTOM que o navegador automaticamente configurará a MARGIM-TOP. Ficando assim:

finalizando a aula, alteraremos a fonte dos nossos textos.
tems nosso HEADER, dentro dele temos 2 H2 e cada uma com sua  classe específica, TITULO e SUBTITULO, para cada uma desta classes daremos tamanhos diferentes.

O tamanho de fonte aqui, nos podemos trabalhar com valor de fonte ABSOLUTO ou RELATIVO, conforme já visto em aulas enteriores.
Em nenhum lugar falamos que a fonte do BODY tinha tamanho, mas ela já vem com um tamanho PADRÃO DO NAVEGADOR, então podemos trabalhar sobre este tamanho com valores VELATIVOS. Podemos por:
    .titulo {
              font-size: 400%; escrever % ou EM é a mesma coisa
              font-size: 4em;   
    
}
Se olharmos os espaçamento entre os H2, veremos uma erro nas MARGENS que já vem por PADRÂO nos elementos H2. Que corrigiremos na proxima AULA.
OBS: Lá no curso de BOOTSTRAP iremos ver a diferença entre PX, PT, EM e %.



 


















            

