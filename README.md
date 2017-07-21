# http-cache
<h1>Como aproveitar o cache do navegador</h1>
Aproveitar o cache do navegador consiste em definir uma data de validade nos cabeçalhos de HTTP para recursos estáticos, instruindo o navegador a carregar os recursos baixados anteriormente a partir do disco local, não através da rede. Se você já usou o PageSpeed, tenho certeza que se deparou com uma mensagem como esta.
<img src="images/1.jpg" />
Nesse artigo vou falar sobre como especificar uma expiração para os recursos armazenáveis em cache que tem uma vida útil de atualização curta.
