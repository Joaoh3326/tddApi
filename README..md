# API com TDD

API construida com BDD, para testar as funcionalidades de login de uma aplicação

## Getting Started

Essas instruções farão com que você tenha uma cópia do projeto em execução na sua máquina local para fins de desenvolvimento.

### Prerequisites

```
- nodejs
- npm
```

### Installing

1° Passo: Execute os comandos abaixo para clonar o repositorio e acessar a pasta:

```
git clone https://github.com/Joaoh3326/tddApi.git

cd tddApi
```

2° Passo: `Crie e Configure os arquivos .env e .env.test:

(localizado) na raiz do projeto.

.env

```
DB_HOST=127.0.0.1
DB_USER=docker
DB_PASS=docker
DB_NAME=nodetdd

```

.env.test

```
DB_DIALECT=sqlite
```

3° Passo: Execute o comando abaixo para installar as depêndecias:

```
npm install ou npm i
```

4° Passo: Execute o comando para rodar em desenvolvimento localmente:

```
npm run dev
```

## Running the tests

Para rodar os testes execute o seguinte comando:

```
npm run test
```

## Built With

- [NODEJS](https://nodejs.org/en/) - Executor de codigo javascript em runtime
- [NPM](https://www.npmjs.com/) - Gerenciador de pacotes
- [EXPRESS](https://expressjs.com/) - Framework para aplicativo web do Node.js
- [SEQUELIZE](http://docs.sequelizejs.com/) - Node.js ORM
- [NODEMAILER](https://nodemailer.com/about/) - Modulo para criação e envio de emails
- [JEST](https://jestjs.io/) - Framework para testes

## Authors

- **João Henrique** - [Facebook](https://www.facebook.com/joao.nomads)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
