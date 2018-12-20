# standard padrões para estudo em HTML e CSS e JS

Aula 35 Iniciando um novo website . Vimos a Aula anterior como usar uma imagem como fundo e como fazer uma transparencia da mesma.

Nesta Aula planejaremos o nosso CSS para que tudo que for COMUM, ou seja as configurações que pertecem a vários elementos sejam feitas somente um seção do CSS, com isto nosso CSS ficará mais Limpo. Um ex. disto foi que  o fizemos com as CLASS TITULO e SUBTITULO. 

Lembrando que 1 ELEMENTO PODE TER VARIAS CLASSES, ou seja nosso ELEMENTO pode ter a classe COMUM, e pode ter "SUBCLASSES" que farão a difenciação deste ELEMENTOS.

Nesta Aula iremos MUDAR a forma do nosso CSS em relação so que está feito na aula 34 para mostrar como podemos gerir ELEMENTOS com classe iguais e "SUBCLASSEs" Desta forma diminuiremos o tamanho do nosso CSS.Desta forma faremos um planejamento.

ficando assim:
OBS: Alteremos o nosso HTML, colocando os H2 com CLASS.TITULOS e com "SUBCLASS.fonte350" e outro com "SUBCLASSfonte300"

 ERA ASSIM:

.titulo, .subtitulo {
            font-family: 'Oswald', sans-serif;
            text-transform: uppercase;
            line-height: 1em; 
            font-weight: 400;
            text-shadow: 3px 3px 0px rgba(0,0,0,.8);
            }

FICOU ASSIM:

.titulo {
            font-family: 'Oswald', sans-serif;
            text-transform: uppercase;
            line-height: 1em; 
            font-weight: 400;
            text-shadow: 3px 3px 0px rgba(0,0,0,.8);
}



.fonte350 {  /*Colocamos aqui blocos para configurar "SUBCLASSES" do h2 chamada FONTE350 */
            font-size: 3.5em;
}
.fonte300 {  /*Colocamos aqui blocos para configurar "SUBCLASSES" do h2 chamada FONTE300 */
            font-size: 3em;    

}

Fizemos com as fontes, e agora faremos com as CORES:
.cinza { /*Classe CINZA pertence somente o H2 do fonte300 */
        color: rgba(203,204,203,1);
}
Com isto nosso TITULO e SUBTITULO estão iguas, agora podemos exluir aquilo que está duplicado.

Com isto, TODO ELEMENTO que queiremos vincular ao tamanho da fonte do TITULO, basta ADICIONARMOS as "subclasses" com o mesmo  nome.

Isto torna nosso CSS mais simple e fácil e lá na frente veremos o resultados deste conceito de CSS. Toda a Vez que pensarmos em CSS, pensaremos em uma COMBINAÇÃO DE CLASSES.

