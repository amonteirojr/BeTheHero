# Be The Hero
> Aplicação completa desenvolvida durante o curso de uma das Semanas Omnistack promovidas pela RocketSeat.

[![NPM Version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Downloads Stats][npm-downloads]][npm-url]

A aplicação tem como objetivo auxiliar e facilitar o contato das ONG's responsáveis por cuidar de animais em situação de 
abandono com pessoas (ou heróis, como tratadas no app) que gostariam de ajudar financeiramente essas ONG's.

![](header.png)

## Installation
> É necessário ter o NodeJS instalado na máquina. Caso ainda não possua, baixe e instale através do [site oficial](https://nodejs.org/en/)

OS X / Linux / Windows:

### Backend

Pelo prompt de comando ou terminal, navegue até a pasta do backend e execute:

```sh
npm install
```

Terminada a instalação das dependências, ainda dentro da pasta do backend execute o comando abaixo para criar o banco de dados:

```sh
npx knex migrate:latest
```

Depois basta executar o comando ```sh npm start``` para que o servidor comece a rodar.


## Usage example

A few motivating and useful examples of how your product can be used. Spice this up with code blocks and potentially more screenshots.

_For more examples and usage, please refer to the [Wiki][wiki]._

## Development setup

Describe how to install all development dependencies and how to run an automated test-suite of some kind. Potentially do this for multiple platforms.

```sh
make install
npm test
```

## Release History

* 0.2.1
    * CHANGE: Update docs (module code remains unchanged)
* 0.2.0
    * CHANGE: Remove `setDefaultXYZ()`
    * ADD: Add `init()`
* 0.1.1
    * FIX: Crash when calling `baz()` (Thanks @GenerousContributorName!)
* 0.1.0
    * The first proper release
    * CHANGE: Rename `foo()` to `bar()`
* 0.0.1
    * Work in progress

## Meta

Your Name – [@YourTwitter](https://twitter.com/dbader_org) – YourEmail@example.com

Distributed under the XYZ license. See ``LICENSE`` for more information.

[https://github.com/yourname/github-link](https://github.com/dbader/)

## Contributing

1. Fork it (<https://github.com/yourname/yourproject/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki
