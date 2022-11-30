# Food Explorer Backend

<h1 align="center">
    <img alt="Food Explorer Backend" title="Food Explorer" src="./.github/capa.png" />
</h1>

<p align="center">
	
  <img src="https://img.shields.io/static/v1?label=PRs&message=welcome&color=49AA26&labelColor=000000" alt="welcome!" />
	
  <img src="https://img.shields.io/github/languages/count/exodogurgel/food-explorer-frontend" alt="languages" />
	
  <img alt="Github License" src="https://img.shields.io/github/license/exodogurgel/food-explorer-frontend" />


</p>

<br>

### 💻 Food Explorer Backend

Building a application API Restful - The application that we will develop is a digital menu for a fictional restaurant, known as foodExplorer.

In this challenge, the following topics were addressed:

Express;
Routes and http method;
Params;
Controllers;
Middleware;
SQL;
Migrations;
Query Builder;
Knex;
JWT;
Disk Storage;
Cors;

Watch it in action Deploy Front: [Click Here](https://food-explorer-rest.netlify.app/)
Watch it in action Deploy Backend: [Click Here](https://food-explorer-jfl3.onrender.com)

Login User: cliente@email.com  
Password: 123456

What was developed:

- [x] A structured project, with a good organization of folders, division of components in the front-end, etc.
- [x] A README.md file with specifications on how to run the project in a dev environment.
- [x] Users must authenticate themselves to enter the application through the login screen, you can apply what you learned in JWT authentication classes. Authentication must be validated with a password.
- [x] The admin will upload images to register the dishes.
- [x] Finally, deploy your application.
- [x] Give your functions and variables meaningful names: work with Clean Code concepts a bit.
- [x] The admin, restaurant and users data will be stored in a database.
- [x] Possibility to search by dish name, ingredients or favorite dish
- [x] It is essential that your interface consumes its own API.
- [x] Interesting to make the application responsive: use the concept of Mobile First that was learned in class.
- [x] It's up to you where to apply animations, transitions, and transformations.
- [x] It meets the model proposed in Figma and contains elements indicative of action and state.
opcionais
- [x] The user can add items to the cart by clicking the add button. The amount is controlled by the “-” and “+” buttons;
- [x] By clicking on the my order button, the user will be redirected to a screen where he will see his order, the sum and the payment methods;
- [x] The user will be able to delete a dish from the cart and the total amount of the order should be updated automatically;
- [x] The user can mark a dish as a favorite, just click on the heart that appears next to each one;
- [x] The admin will view and control the status of each order, through a select field. Orders will appear in a table when you click Orders;
---
<br />
## 🧪 Tools

Application developed using the following tools:

- [NodeJS](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)
- [KnexJS](http://knexjs.org/)
- [CORS](https://expressjs.com/en/resources/middleware/cors.html)
- [Multer](https://github.com/expressjs/multer)
- [SQLite](https://github.com/mapbox/node-sqlite3)
- [Insomnia](https://insomnia.rest/download)
- [Beekeeper Studio](https://www.beekeeperstudio.io/)
- [Javascript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)

## 🚀 Getting started

Clone Project and access folder and start the server it is necessary to have NodeJs, Git
installed and Visual Studio Code.

### Programs needed to Getting started

- [NodeJS](https://nodejs.org/en/)
- [Visual Studio Code - Vscode](https://code.visualstudio.com/)
- [Git](https://git-scm.com/)
- [Insomnia](https://insomnia.rest/download)
- [Beekeeper Studio](https://www.beekeeperstudio.io/)

This project is divided into two parts:
1. Backend (food-explorer-api folder) 
2. Frontend (food-explorer folder)

💡 The Frontend needs the Backend to be running to work.

<br />

### Install server and start up

```bash
# Clone this repository
$ git clone https://github.com/felipe-gomes-vicente/food-explorer-api.git

# Access the project folder in your terminal
$ cd food-explorer-api

# Install the dependencies
$ npm install

# run the migration and seed
$ npm migrate
$ npm seed

# Run the application in development mode
$ npm run dev

# Admin login
$ email: admin@email.com
$ password: 0908

# Client login
$ email: cliente@email.com
$ password: 123456

# The Server will start at port: 3333 - go to http://localhost:3333
```

<br />

Clone the Food Explorer Frontend project and access the folder

```bash
# Clone this repository
$ git clone https://github.com/felipe-gomes-vicente/food-explorer.git

# Access the project folder in your terminal
$ cd food-explorer

# Install the dependencies
$ npm install

# Run the application in development mode
$ npm run dev

# The application will open on the port: 3000 - go to http://localhost:5173/ or http://127.0.0.1:5173/ 
```

<br />

## 📝 License

This project is under the MIT license. See the file [LICENSE](LICENSE) for more details.

---

&nbsp;

<p align="center">Done with 💜 by Felipe Vicente👋</p>

- ## My LinkedIn - [![Linkedin Badge](https://img.shields.io/badge/-FelipeVicente-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/felipe-gomes-vicente/)](https://www.linkedin.com/in/felipe-gomes-vicente/)
