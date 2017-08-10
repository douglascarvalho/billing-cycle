# Billing Cycle

**billing-cycle** foi desenvolvido através de um curso MEAN. A aplicação funciona como um gerenciador de finanças, onde o usuário pode adicionar créditos e débitos, especificando sua natureza e visualizando um total através de um dashboard.

## Tecnologias
* **node-js** - utilizando para criar RESTful Web Service (backend do projeto);
* **express-js** - framework web minimalista para node.js;
* **angular-js 1.6.3** - tecnologia para desenvolver e gerenciar o front-end;
* **MongoDB** - base de dados NOSQL;
* **bootstrap 3** - paginas responsivas;
* **npm** - gerenciador de pacotes do node.js;
* **gulp** - para build, servidor dev, automatização e taks como juntar todos os arquivos js e css em um "minified";
* **pm2** - gerenciador de processos para node.js

## Demo
Foi realizado deploy do projeto no Heroku, que pode ser acessado neste link: 
[Heroku](https://billing-cycle.herokuapp.com/)

**Nota:** Talvez demore alguns segundos para abrir pois o Heroku desliga os dynos quando o servidor para de receber requisições.

## Para realizar o Build e iniciar o servidor

Garanta que o Mongo esteja rodando. 

Backend:
```
$ npm run production
```
Angular:
```
$ npm run dev
```
Automaticamente a página será aberta no browser, caso não abrir acesse:
```
http://localhost:3000
