<h1 align="center">ecoleta</h1>

### ❓️ O que é 
<p>
  O ecoleta foi um projeto desenvolvido durante a Next Level Week, criado pela 
  <a href="https://blog.rocketseat.com.br/primeira-next-level-week/">Rocketseat</a>, focado no desenvolvimento de uma aplicação completa, do back end ao mobile,
  usando as tecnologias NodeJS, ReactJS e React Native.
</p>

### 🎯️ Objetivo
<p>
  A ideia principal do aplicativo é conectar pessoas que queiram realizar o descarte consciente de seu lixo com pontos de coleta específicos, filtrando por
  tipo de lixo.
</p>

### ⚙️ Tecnologias

O projeto foi construído utilizando as ferramentas descritas abaixo:

#### **Back end**  ([NodeJS](https://nodejs.org/en/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[Express](https://expressjs.com/)**
-   **[CORS](https://expressjs.com/en/resources/middleware/cors.html)**
-   **[KnexJS](http://knexjs.org/)**
-   **[SQLite](https://github.com/mapbox/node-sqlite3)**
-   **[ts-node](https://github.com/TypeStrong/ts-node)**
-   **[dotENV](https://github.com/motdotla/dotenv)**
-   **[Multer](https://github.com/expressjs/multer)**
-   **[Celebrate](https://github.com/arb/celebrate)**
-   **[Joi](https://github.com/hapijs/joi)**

#### **Front end**  ([React](https://reactjs.org/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[React Router Dom](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-dom)**
-   **[React Icons](https://react-icons.github.io/react-icons/)**
-   **[Axios](https://github.com/axios/axios)**
-   **[Leaflet](https://react-leaflet.js.org/en/)**
-   **[React Leaflet](https://react-leaflet.js.org/)**
-   **[React Dropzone](https://github.com/react-dropzone/react-dropzone)**

#### **Mobile**  ([React Native](http://www.reactnative.com/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[Expo](https://expo.io/)**
-   **[Expo Google Fonts](https://github.com/expo/google-fonts)**
-   **[React Navigation](https://reactnavigation.org/)**
-   **[React Native Maps](https://github.com/react-native-community/react-native-maps)**
-   **[Expo Constants](https://docs.expo.io/versions/latest/sdk/constants/)**
-   **[React Native SVG](https://github.com/react-native-community/react-native-svg)**
-   **[Axios](https://github.com/axios/axios)**
-   **[Expo Location](https://docs.expo.io/versions/latest/sdk/location/)**
-   **[Expo Mail Composer](https://docs.expo.io/versions/latest/sdk/mail-composer/)**

### 🚀️ Como executar

Este projeto é divido em três partes:
1. Backend (pasta backend) 
2. Frontend (pasta frontend)
3. Mobile (pasta mobile)

Obs: para que o front end e o aplicativo mobile funcionem corretamente, é necessário que o back end esteja sendo executado.

### Pré-requisitos

É necessário que você tenha instalado em sua máquina o [Git](https://git-scm.com) para clonar o projeto, o [Node.js](https://nodejs.org/en/) para que seja
iniciado para execução do back e do front end, e o [Expo](https://expo.io/) para execução do projeto mobile.

#### Clonando o projeto

```bash

# Clone este repositório
$ git clone https://github.com/lsantoro07/nlw-01-ecoleta.git

# Acesse a pasta do projeto no terminal/cmd
$ cd nlw-01-ecoleta

```

#### Iniciando o servidor

```bash

# Na pasta raiz do projeto que clonado, vá para a pasta backend
$ cd backend

# Instale as dependências
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ yarn dev

# O servidor inciará na porta:3333 - acesse http://localhost:3333 

```

#### Rodando a aplicação web (Frontend)

```bash

# Na pasta raiz do projeto que clonado, vá para a pasta da aplicação Front End
$ cd frontend

# Instale as dependências
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ yarn start

# A aplicação será aberta na porta:3000 - acesse http://localhost:3000

```

#### Rodando a aplicação mobile

```bash

# Na pasta raiz do projeto que clonado, vá para a pasta da aplicação mobile
$ cd mobile

# Instale as dependências
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ yarn start

# O metro bundler do Expo será executado na porta:19002 e estará disponível para conexão seu device através do aplicativo do Expo - acesse http://localhost:19002/

```
### 👨‍💻️ Autor

[Leandro Santoro](https://www.linkedin.com/in/leandro-santoro-237a6218b/) 
<br /><br />
[![Email Badge](https://img.shields.io/badge/-lsantoro07%40outlook.com-blue?style=flat-square&logo=Gmail&logoColor=white&link=mailto:lsantoro07@outlook.com)](mailto:lsantoro07@outlook.com)




