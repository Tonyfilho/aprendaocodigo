# standard padrões para estudo em HTML e CSS e JS

Aula 32 Iniciando um novo website . Daremos divições ao nosso SITE, com valores SEMÂTICOS, usando elementos especificos de cada DIVISÃO.

No video anterior usamos as propriedades de BACKGROUND para usarmos , centralizarmos e pormos como fundo fixo, e além de fazermos se comportar em dispositivos móveis de forma a adapta -se.

Neste video aprenderemos a usar um propriedade do BACKGROUND que é background-image: linear-gradient() Onde dentro dos () podemos definir cores , que em nosso caso usaremos padrões RGBA

Usaremos um efeito de escurecer a imagem para darmos uma visualização melhor dos nosso textos que ficarão sobre a imagem. Não faremos isto na Maquina, pois a imagem se encontra na NUVEM, então teremos que usar as propriedades do CSS para fazermos isto. É isto que faremos na próxima aula.

como o CSS tem efeito em cascata,teremos que por esta propriedade junto  e na mesma linha do BACKGROUND já existente ficando assim.

Existe 2 forma de trabalhar o BACKGROUND-IMAGE:
a 1º é usando uma URL onde informamos o caminho da imagem. Seja local ou na nuvem.

background: url(https://img.youtube.com/vi/GvbzrqD_kno/maxresdefault.jpg);

A 2ª é usando é usando uma propriedade chamada LINEAR-GRADIENT. Que podemos ver logo abaixo um ex.
background-image: linear-gradient(red, orange, blue, green); Assim que recarregarmos iremos ver um DEGRADE como imagem.

Mas caso queiramos escurecer uma imagem ou um video, podemos mixar estas propriedades para termos  um resultado, usando o RGBA como cor.Usando  uma imagem com TRANSPARÊNCIA.

background-image: linear-gradient(rgba(0,0,0,.1), rgba(0,0,0,.9)), url(https://img.youtube.com/vi/GvbzrqD_kno/maxresdefault.jpg);

















            

