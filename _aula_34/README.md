# standard padrões para estudo em HTML e CSS e JS

Aula 34 Iniciando um novo website . Vimos a Aula anterior como usar uma imagem como fundo e como fazer uma transparencia da mesma.

Nesta aula colocaremos Iremos ver qual a fonte que iremos usar. Como usamos o site www.movieclips.com ou outro site que queiremos usar como Base e se mandarmos INSPENCIONAR o ELEMENTO, conseguiremos descobri varias  informações.

Vimos em aulas  passada que carregamos uma familia de fontes, caso a maquina ou o navegador ou celular  não tenha a fonte que nosso site use.

Neste caso, usaremos o GOOGLE.COM/FONTS, e pesquisamos uma fonte chamada OSWALD e pegamos o link para o CSS, caso o site do google pare de funcionar, nossa pagina usãrá uma fonte padrão definida por nós.

@import url('https://fonts.googleapis.com/css?family=Oswald:400,700');


Temos um espaço entre os texto que são a altura da linha que ajustaremos com paramentro LINE-HEIGTH, além de já por o texto em letra maiuscula.

.titulo, .subtitulo {
              font-family: 'Oswald', sans-serif;
              text-transform: uppercase;
              line-height: 1em; 
              font-weight: 400;
              text-shadow: 3px 3px 0px rgba(0,0,0,.8);
    
}

font-weight: 400; Podemos reparar que o texto não ficou legivel, por que Visto usamos um H2 por padrão , todo H2 já vem com o BOLD nele carregado, por isto teremos que dizer que não queremos o BOLD, ou indicar na  fonte se o tamanho que queremos é o 400 ou 700 conforme o que escolhemos.

Text-shadow é para por uma sombra no nosso texto.

         offset-X que o espanhamento na VERTICAL
         offset-Y que  é o espalhamento na HORIZONTAL
         BLUR que é borrado da cor
         COR que será a cor do text-shadow













            

