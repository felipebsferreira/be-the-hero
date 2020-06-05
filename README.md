<h1 align="center">
    <img src="frontend/src/assets/logo.svg">
</h1>

<!-- <h1 align="center">
    <img src="frontend/src/assets/Kapture_2020-06-04_at_21.22.50.gif">
</h1> -->

<!-- <h3 align="center">
    <a href="#">Acessar a demonstração</a>
</h3> -->

# 🗂 Indice

- [Sobre](#-sobre)
- [Lista das Tecnologias Utilizadas](#-lista-das-tecnologias-utilizadas)
- [Como baixar e rodar o projeto](#-como-baixar-e-rodar-o-projeto)

## 📝 Sobre

O projeto **Be The Hero** é um sistema de doação para ONGs que foi criado durante a **Semana Omnistack 11** da [Rocketseat](https://rocketseat.com.br).

O sistema inclui uma **API** no **backend**, desenvolvido em [NodeJS](https://nodejs.org/), que fornece serviços para consulta, cadastro, atualização e deleção de ONGs e incidentes em um banco de dados [SQLite](https://www.sqlite.org/index.html), além de controle de acesso de perfil de usuário.

O **frontend** da aplicação foi desenvolvido com [ReactJS](https://reactjs.org) e a comunicação com a **API** do **backend** foi feita com [Axios](https://github.com/axios/axios).

Também foi desenvolvida uma aplicação **mobile** com [React Native](https://reactnative.dev) que também se comunica com o **backend** por meio do *Axios*.

## 🛠 Lista das Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- [ReactJS](https://reactjs.org)
- [React Native](https://reactnative.dev)
- [NodeJS](https://nodejs.org/)
- [Axios](https://github.com/axios/axios)
- [SQLite](https://www.sqlite.org/index.html)
- [KnexJS](http://knexjs.org)
- [Expo](https://expo.io)

## 📦 Como baixar e rodar o projeto

```bash
# Clonar o repositório
$ git clone https://github.com/felipebsferreira/be-the-hero
```

### Rodar a API

```bash
# Entrar no diretório do backend
$ cd be-the-hero/backend

# Instalar as dependências do backend
$ yarn install

# Instalar o KnexJS para executar as migrations do banco de dados
$ npm install knex -g

# Iniciar a API do backend
$ yarn start
```

### Acessar o Frontend da aplicação

```bash
# Entrar no diretório do frontend
$ cd ..
$ cd frontend

# Instalar as dependências do frontend
$ yarn install

# Iniciar o frontend
$ yarn start

```

### Acessar a aplicação mobile

```bash
# Entrar no diretório da aplicação mobile
$ cd ..
$ cd mobile

# Instalar as dependências da aplicação mobile
$ yarn install

# Iniciar a aplicação via expo
$ expo start

# Com seu smartphone, aponte a câmera para o QR code que irá aparecer no seu browser
```

---
Desenvolvido por Felipe Alberto B. S. Ferreira