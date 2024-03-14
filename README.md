# analise-codigo-js

# PRIMEIRO CODIGO
 ![](/img/capitura.png)

 * O primeiro código ele abre uma página e aparecerá uma mensagem na tela em 3 segundos contando  com segintes códigos

 * timeMsg() tem a função de chamada quando o link é clicado. Ela define um temporizador que aguarda três segundos (3000 milissegundos) antes de chamar a função alertMsg().

 * função alertMsg() após três  segundos é chamada, como definido pela função timeMsg(). Ela escreve o texto "Terminal Root" no documento usando document.write().

 *  (<a>) tem um evento onClick que dispara a função timeMsg() quando clicado. Isso faz com que a mensagem "Terminal Root" só apareça após três segundos de espera.



 # SEGUNDO CODIGO
![](/img/capitura2.png)
 * var str = 'Terminal Root';
 
 * Declara uma variável chamada str e atribui a ela a string 'Terminal Root'.
str = str.replace("Root", "Linux");
 
* Utiliza o método replace() para substituir a primeira ocorrência da substring "Root" na variável str pela substring "Linux". O resultado da substituição é armazenado de volta na variável str.
document.write(str);
 
Escreve o valor atual da variável str no documento HTML, resultando em "Terminal Linux" sendo exibido na página.