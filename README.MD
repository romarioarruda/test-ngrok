### Criando um túnel http com ngrok para tornar aplicações no localhost acessiveis na internet



> Instale as dependencias do Node

```
$ npm install
```

> Rode a aplicação no localhost, na porta desejada. Neste exemplo, uso a porta 3000

```
$ npm start
```

> Com o localhost up, execute o túnel usando o script ngrok indicando a porta que a aplicação local está rodando

```
$ ./ngrok http 3000

ou

$ npm run ngrok
```

Agora é só acessar a aplicação através do link gerado pelo NGROK.

***Exemplo do resultando no terminal:***

<img src="./exemple.png" alt="ngrok hosts" heigth="80" width="600"/>


<br><br>

***Links úteis***:

[Página do ngrok](https://ngrok.com/)
