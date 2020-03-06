# CSS
CSS:do Inglês, Cascading Style Sheet, é usado para estilizar elementos escritos em uma linguagem de marcação como HTML.

Utilizando o CSS é possível alterar a cor do texto e do fundo, fonte e espaçamento entre parágrafos. Também pode criar tabelas, usar variações de layouts, ajustar imagens para suas respectivas telas e assim por diante.

CSS foi desenvolvido pelo W3C (World Wide Web Consortium) em 1996, por uma razão bem simples. O HTML não foi projetado para ter tags que ajudariam a formatar a página. Você deveria apenas escrever a marcação para o site.
A relação entre HTML e CSS é bem forte. Como o HTML é uma linguagem de marcação (o alicerce de um site) e o CSS é focado no estilo (toda a estética de um site), eles andam juntos.

Com o Cascading Style Sheets é possível criar animações complexas, criar efeitos com uso de parallax, que faz parecer que a imagem de fundo tem uma profundidade diferente um dos outros, criar sites interativos e também jogos com HTML5 e CSS3.

## Seletores:  um dos mais poderosos aspectos CSS, permite que selecionemos qualquer elemento na página para estilizar.
## Seletor de tipo:
este é o tipo de seletor que utilizamos nos exemplos até agora. Com este seletor, selecionamos todas as tags de um mesmo tipo. Por exemplo, se digitamos a estaremos selecionando todas as tags a (links) da página e poderemos aplicar estilos a elas. Útil para estilos gerais, mas para maior especificidade utilizamos outros seletores.
## Seletor descendente: 
com este seletor, podemos escolher um ou mais elementos que estão dentro de outro, ou seja, que são descendentes do elemento principal. Exemplo: p strong. Com isso, selecionamos apenas tags strong que estão dentro de parágrafos. Podemos selecionar com ainda mais especificidade, escrevendo mais elementos, como: div p strong a. Neste exemplo, selecionamos links que estão dentro de tags strong que estão dentro de parágrafos que estão dentro de tags div.
## Seletor de classe: 
seleciona elementos com uma classe específica aplicada.
## Seletor de id: 
seleciona o elemento com a id especificada.
## Referências CSS
### CSS Interno
Código CSS interno é colocado na seção <head> de uma determinada página. As classes e IDs podem ser usados para se referir ao código CSS, mas eles só estão ativos nessa página específica.O CSS interno é colocado entre tags <style></style>. 
exemplo:
  <head>
<style type="text/css">
p {color:white; font-size: 10px;}
.center {display: block; margin: 0 auto;}
#button-go, #button-back {border: solid 1px black;}
</style>
</head>
  
### CSS externo
Provavelmente a maneira mais conveniente de adicionar CSS ao seu site, é vinculá-lo a um arquivo .css externo. Dessa forma, quaisquer alterações feitas em um arquivo CSS externo serão refletidas em seu site globalmente. Uma referência a um arquivo CSS externo é colocada na seção <head> da página:
 exemplo:
  <head>
<link rel="stylesheet" type="text/css" href="style.css" />
</head>
### CSS inline
  O CSS inline é usado para uma tag HTML específica. O atributo <style> é usado para formatar uma tag HTML específica.
exemplo:
  <!DOCTYPE html>
<html>
<body style="background-color:black;">

<h1 style="color:white;padding:30px;">Hostinger Tutorials</h1>
<p style="color:white;">Something usefull here.</p>

</body>
</html>
  
  
