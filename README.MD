### Criando um túnel http com ngrok para tornar aplicações no localhost acessiveis na internet
<br><br>


**Siga os passos**:

* Instale as dependencias do Node

```
$ npm install
```

* Rode a aplicação no localhost, na porta desejada. Neste exemplo, uso a porta 3000

```
$ npm start
```

* Com o localhost up, execute o túnel usando o script ngrok indicando a porta que a aplicação local está rodando

```
$ ./ngrok http 3000

ou

$ npm run ngrok
```

<br>

***Exemplo do resultando no terminal:***

<img src="./exemple.png" alt="ngrok hosts" heigth="80" width="600"/>

<br>

**Acesse o link gerado. Exemplo**:

> https://7a3e-168-181-253-141.ngrok.io/
> 
<br><br>

***Links úteis***:

[Página do ngrok](https://ngrok.com/)
