# spotify-imersao-alura

### Execução do campo de busca
Para fazer o campo de buscar funcionar com a API, é preciso instalar o json-server

Para isso deve-se usar o comando:
~~~powershell
npm install -g json-server@0.17.4
~~~

Caso esteja utilizando outra versão, utilize o comando abaixo antes de instalar a versão 0.17.4:
~~~powershell
npm uninstall -g json-server`
~~~

Depois para executar o json-server, utilize o código a seguir (utilize de preferência o terminal bash, pois o powershell não funciona corretamente):
~~~powershell
json-server --watch api-artists/artists.json --port 3000 --port 3000`
~~~