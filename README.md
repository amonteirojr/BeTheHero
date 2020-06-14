<img src="frontend/src/assets/logo.svg">

# Be The Hero
> Aplicação completa desenvolvida durante o curso de uma das Semanas Omnistack promovidas pela RocketSeat.

A aplicação tem como objetivo auxiliar e facilitar o contato das ONG's responsáveis por cuidar de animais em situação de 
abandono com pessoas (ou heróis, como tratadas no app) que gostariam de ajudar financeiramente essas ONG's.


#### Índice
1. [Instalação](#install)

    1.1. [Backend](#backend)  
    1.2. [Frontend](#frontend)  
    1.3. [Mobile](#mobile)
  
2. [Screenshots](#screenshots)


*********************************

<div id='install'/> 

## Instalação
> É necessário ter o NodeJS instalado na máquina. Caso ainda não possua, baixe e instale através do [site oficial](https://nodejs.org/en/)

Todos os procedimentos são iguais para OS X, Linux ou Windows:


<div id='backend'/> 

### Backend

Pelo prompt de comando ou terminal, navegue até a pasta do backend e execute:
```sh
npm install
```
Terminada a instalação das dependências, ainda dentro da pasta do backend execute o comando abaixo para criar o banco de dados:
```sh
npx knex migrate:latest
```
Depois basta executar o comando ```npm start``` para que o servidor comece a rodar.


<div id='frontend'/> 

### Frontend

Pelo prompt de comando ou terminal, navegue até a pasta do front e execute:
```sh
npm install
```
Após o término da instalação das dependências, basta executar o comando ```npm start```. 
A aplicação será executada na porta 3000. Seu navegador será aberto automaticamente. Caso isso não acontaça,
abra o navegador e acesse "http://localhost:3000".


<div id='mobile'/> 

### Mobile

Pelo prompt de comando ou terminal, navegue até a pasta do mobile e execute:
```sh
npm install
```
Após o término da instalação das dependências, basta executar o comando ```npm start```.
Como o mobile foi desenvolvido utilizando o Expo, será aberta uma janela no seu navegador. Nela, você terá 
várias opções disponíveis para executar o app. Caso tenha o Expo instalado em seu smartphone (Android ou iPhone) 
basta ler o QRCode disponível nada tela. 


<div id='screenshots'/> 

## Screenshots

#### Web

<img src="/screenshots/web/MainPage.PNG" width="600"/>

<img src="/screenshots/web/RegisterPage.PNG" />

<img src="/screenshots/web/OngPage.PNG" />

<img src="/screenshots/web/NewIncidentPage.PNG" />



#### Mobile

<img src="/screenshots/mobile/MainPage.PNG" height="600" align="center"/>
<img src="/screenshots/mobile/DetailPage.PNG" height="600" align="center"/>
