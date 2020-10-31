# GOStack desafio 09

[![node version](https://img.shields.io/node/v/react)](https://img.shields.io/node/v/node)
![npm](https://img.shields.io/npm/v/pg?label=Postgres)
![npm](https://img.shields.io/npm/v/typeorm?label=typeorm)
<img src="https://img.shields.io/github/languages/top/tsunodajapa/gostack_desafio_09">

Este desafio tem como objetivo utilizar alguns apredizados do Gostack da Rocketseat.

## Conceitos estudados

- Conceitos avançados de SOLID;
- Conceitos de DDD
- Typeorm com banco postgres
- Migrations
- Relacionamentos ManyToMany

## Requisitos de instalação

- npm >= 6.0.0
- node >= 10
- Banco de Dados Postgres

## Como utilizar

#### Atualize o arquivo ormconfig.json com os dados do seu banco.

#### Execute o comando para instalações de dependências do servidor:

```
yarn
```

#### Execute o comando para rodar as Migrations, que criará as tabelas no banco:

```
npm run typeorm migration:run

ou

yarn typeorm migration:run
```

#### Iniciar o servidor:
```
yarn dev:server
```
