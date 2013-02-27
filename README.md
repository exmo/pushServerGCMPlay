Serviço GCM com o Play Framework
=================

Serviço em Rest/Json desenvolvido para realizar o envio de mensagens Push para 
smartphones Android através do Google Cloud Messaging (GCM). O serviço foi desenvolvido somente com o Play Framework.

Para executar, basta baixar e executar o comando "play clean compile run" dentro da pasta do projeto. Lembre-se de 
colocar o seu SenderID e Key no arquivo controllers/Push.java. Também é necessário alterar o arquivo conf/application.conf
com as informações do seu banco de dados.
