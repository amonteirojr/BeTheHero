# Be The Hero
> Aplicação completa desenvolvida durante o curso de uma das Semanas Omnistack promovidas pela RocketSeat.


A aplicação tem como objetivo auxiliar e facilitar o contato das ONG's responsáveis por cuidar de animais em situação de 
abandono com pessoas (ou heróis, como tratadas no app) que gostariam de ajudar financeiramente essas ONG's.

![](C:\Users\admon\Desktop\beTheHero\Web\MainPage.PNG)

## Instalação
> É necessário ter o NodeJS instalado na máquina. Caso ainda não possua, baixe e instale através do [site oficial](https://nodejs.org/en/)

Todos os procedimentos são iguais para OS X, Linux ou Windows:


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


### Frontend

Pelo prompt de comando ou terminal, navegue até a pasta do front e execute:

```sh
npm install
```

Após o término da instalação das dependências, basta executar o comando ```npm start```. 
A aplicação será executada na porta 3000. Seu navegador será aberto automaticamente. Caso isso não acontaça,
abra o navegador e acesse "http://localhost:3000".


### Mobile

Pelo prompt de comando ou terminal, navegue até a pasta do mobile e execute:

```sh
npm install
```

Após o término da instalação das dependências, basta executar o comando ```npm start```.
Como o mobile foi desenvolvido utilizando o Expo, será aberta uma janela no seu navegador. Nela, você terá 
várias opções disponíveis para executar o app. Caso tenha o Expo instalado em seu smartphone (Android ou iPhone) 
basta ler o QRCode disponível nada tela. 
