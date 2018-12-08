# standard padrões para estudo em HTML e CSS e JS

Entendendo como o navegador lê o nosso código HTML

Como funciona o FLUXO dos elementos dentro da nossa tela:

O que é um fluxo de elemento na nossa tela? É quando o navegador define uma posição de um elemento na tela, pela posição do elemento PAI, ou seja o elemento anterior.

Se dermos um espaço no pelo EDITOR , veremos que o navegador irá ignora-lo, destaforma veremos que não haverá espaço no entre as linhas do navegador, se formo INSPECIONAR O ARQUIVO, veremos o espaço que colocamos no arquivo pelo EDITOR, mas NÃO veremos o espaço no NAVEGADOR, ou seja : Se o texto tiver uma quebra de linha o mesmo não aparecerá no navegador.

O porque ? Que quando definimos uma margem para todos lados de 20PX, o lado direito ficará com uma margem muito maior que 20PX. Arespota disto é :
        Existe um INTERPRETADOR em todos navegadores que irá ler o nosso codigo e tentar entende-lo.E gerar um modelo de objeto ideal, gerando um arvore de objetos chamanda de DOM.
       
        Existe tb o RENDERISADOR que  assim que receber DOM do cod do INTERPRETADOR, o RENDERISADOR  irá  pinta-lo e corrigi-lo quando necessário. assim que fizer, ele desenhará na tela .

        O REDERINSADOR só entende as margens, então ele sabe que o ultimo objeto quem que ficar a BAIXO do objeto anterior, ou seja o opjeto PAI.

        Então a ÚNICA forma que o  RENDERISADOR tem de fazer isto é AUMENTAR a MARGEM do lado DIREITO para corrigir isto.

        Lembrando que a DIV por PADRÂO abre com a lagura do objeto PAI que é BODY, se COMENTARMOS A LINHA 25 que é  "width: 250px; conf. as DIVs .left, .right, .center , veremos que o navegador expandirar as DIVS até  o linite da DIV para o limite do elemento PAI que é o BODY. com isto  o proximo elemento ao invez de ir para lado, sempre será configurado para baixo.

        Ou seja por PADRÂO o FLUXO sempre será VERTICAL. Amedida que formos digitando os texto, eles irão ir para DIREITA ate acabar o ESPAÇO DA LARGURA OU  seja WIDTH vido após a quebra do espaço, caso precise de ser posto HORIZONTAL  o mesmo terá que ser editado no CSS.

        A CONFIGURAÇÃO PADRÃO  nada mais é que uma PROPRIEDADE que o NAVEGADOR colocou no mosso cod um elemento. que é : DISPLAY:BLOCK; Quando pedimos para inspecionar um elemento, poderemos ver TODAs a propriedades que o navegador colocou em nosso elementos, nomalmente em VERMELHO na opção INSPECIONAR.

        É esta propriedade achada DISPLAY:BLOCK  que determina  que o nosso objeto  vai ocupar a WIDTH do objeto PAI, ou seja no nosso BODY , isto gera uma quebra de linha com o nosso proximo elemento.
        Se alteremos ou dermos um overwrite na propriedade DISPLAY:BLOCK , conseguiremos mudar isto.

        na próxima aula veremos 2 forma de alterar esta propriedade padrão do navegador.




