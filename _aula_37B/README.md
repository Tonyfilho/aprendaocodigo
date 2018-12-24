# standard padrões para estudo em HTML e CSS e JS

Na Aula anterior vimos como criar e distribuir nossos 3 elementos na parte superior da tela. Mas estes elementos não ficaram da forma que definimos no nosso MOCKUP

Aula 37,Nesta Aula continuaremos Usando POSITION e DISPLAY: FLEX para posicionar nossos elementos HTML (2a Parte) por o Barner sobre

Conforme o MOCKUP nosso BANNER n deveria ficar nesta posição no TOP, mas TB centralizado ,  o BANNER tem que ficar centralizado, a LOGO fixada a esquerda  e a MARCA FACEBOOK fixada a direita. Neste tamanho de tela aparentemente não tem tanta diferença, mas em telas de 2500pixels de largura,  veremos a diferença.

Então, depois de usarmos o DISPLAY:FLEX no PAI , iremos usar POSITION:ABSOLUTE; para pormos estes elementos FILHOs no lugar, e corrigir para posição que requemos.

então usaremos uma nova forma de  posicionamento que ainda não vimos.
1º Criamos uam DIV PAI que já tem WIDHT e HEIGHT definidas, e chamamos ela de PARTE SUPERIOR , "iremos por background-color:green; somente para facilitar nosso entendimento"

O motivo de termos as DIVs no banner e não usarmos a DIV PAI para que o FLEX centraliza-se . É porque dentro desta DIV, teremos um codigo ANÚNCIO para por o link do BANNER, este CODIGO pode ser uma IMAGEM ou uma PAGINA WEB, isto é chamado de "ELEMENTO IFRAME" quando formos fazer o JS faremos o link, mas por enquanto temos q ter esta BANNER no lugar para representar deste site de TERCEIROS, tipo GOOGLE ADS, GOOGLE ADS SENCE, vai colocar o codigo aqui dentro, e este CODIGO n teremos controle dele, sobre ALINHAMENTO, ALTURA , então NÓS só poderemos controlar a DIV que terá este o BANNER.

E esta DIV filho, está sendo controlada pela DIV PAI que é chamada de PARTE_SUPERIOR. E temos esta IMAGEM deste BANNER somente para exemplificar o vermos o local onde o ANÚNCIO do BANNER ficará.

Então , colocaremos FORA da DIV PARTE_SUPERIOR,as DIVs do LOGO e a DIV do FACEBOOK, ficando assim:

Usando POSITION e DISPLAY: FLEX para posicionar nossos elementos HTML (2a Parte)













