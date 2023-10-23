# node.js
Aprendendo node js - acesse os sites de referências - 1-https://www.w3schools.com/nodejs/nodejs_get_started.asp e depois o site  https://nodejs.org/en


O site oficial do Node.js tem instruções de instalação para Node.js: https://nodejs.org

Começando
Depois de baixar e instalar o Node.js em seu computador, vamos tentar exibir “Hello World” em um navegador da web.

Crie um arquivo Node.js chamado "myfirst.js" e adicione o seguinte código:

meu primeiro.js

var http = require('http');

http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/html'});
  res.end('Hello World!');
}).listen(8080);
Salve o arquivo em seu computador: C:\Users\ Seu Nome \myfirst.js

O código diz ao computador para escrever “Hello World!” se alguém (por exemplo, um navegador da web) tentar acessar seu computador na porta 8080.

Por enquanto, você não precisa entender o código. Isso será explicado mais tarde.

Interface da Linha de comando
Os arquivos Node.js devem ser iniciados no programa "Command Line Interface" do seu computador.

Como abrir a interface de linha de comando em seu computador depende do sistema operacional. Para usuários do Windows, pressione o botão Iniciar e procure por “Prompt de Comando”, ou simplesmente escreva “cmd” no campo de pesquisa.

Navegue até a pasta que contém o arquivo "myfirst.js", a janela da interface da linha de comando deve ser semelhante a esta:

C:\Users\Your Name>_
Inicie o arquivo Node.js
O arquivo que você acabou de criar deve ser iniciado pelo Node.js antes que qualquer ação possa ocorrer.

Inicie sua interface de linha de comando, escreva node myfirst.jse pressione Enter:

Inicie "myfirst.js":

C:\Users\Your Name>node myfirst.js
Agora seu computador funciona como um servidor!

Se alguém tentar acessar seu computador na porta 8080, receberá uma mensagem "Olá, mundo!" mensagem em troca!

Inicie seu navegador de internet e digite o endereço: http://localhost:8080
