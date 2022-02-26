# APACHE-2-ERROR-404
CUSTOMIZAR A PAGINA 404 APACHE2

acesse este caminho no terminal Linux

~$ cd  /etc/apache2/sites-enable

siga os passos abaixo

![apache2404](https://user-images.githubusercontent.com/79322362/155826450-37711955-5936-4f21-8712-9def316493c1.png)

agora com o nano , você precisa acrescentar uma linha  exemplo: ErrorDocument 404 http://10.0.0.102/error.html


![apache2404nano](https://user-images.githubusercontent.com/79322362/155826562-aa30d9c7-0bd8-4a35-81fd-6a93e93ee8cc.png)

ficará igual a imagem abaixo

![apache24043](https://user-images.githubusercontent.com/79322362/155826708-fc01aee8-fbe5-42a0-bf89-232c08badd8a.png)

para salvar Ctrl + o 

para sair Ctrl + x

ATENÇÃO, NÃO MUDE O NOME DO ARQUIVO!


por ultimo vocẽ precisa dar restart no apache.

![restartapache2](https://user-images.githubusercontent.com/79322362/155827538-d8521557-9093-4354-9233-27aa85d99808.png)

