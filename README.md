# The Complete Guide To Building A REST API With Node, Express, TypeScript & MongoDB

Thanks Antonio Erdeljac for this wonderful tutorial. 
If you want to see original repo: https://github.com/AntonioErdeljac/ts-node-mongo-rest-api-tutorial

This is a repository for a REST API tutorial using Node, Express, Typescript & MongoDB.

[Video Link](https://youtu.be/b8ZUb_Okxro)

Features:

- Environment, Typescript, Nodemon setup
- MongoDB & Mongoose connect, Database creation
- Controllers creation
- Middlewares creation
- Cookie based authentication
- Postman testing
- Create, Read, Update

### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
git clone https://github.com/AntonioErdeljac/ts-node-mongo-rest-api-tutorial.git
```

### Install packages

```shell
npm i
```

### Setup MongoDB URL

In `src/index.ts`:

```js
const MONGO_URL = ''; // DB URI
```

### Start the app

```shell
npm start
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `start`         | Starts a development instance of the app |