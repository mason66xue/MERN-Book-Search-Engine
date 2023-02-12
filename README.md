# MERN-Book-Search-Engine

## Table of Contents

- [Description](#description)
- [Technology](#Technology)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contribution](#contribution)
- [Questions](#questions)

## Description:

The book search engine is fully build under the MERN stack. Usage of goodle API to create GraphQL with Apollo Server. With this application, the user can sign up and login into the account. Once they sign into their account, they can search the book, save the book, delete the book. 

## Technology:

Project is created with:

- MongoDB
- Express.js
- React.js
- Node.js
- JavaScript
- GraphQL API
- Apollo Server

## Installation

To run this project, install it locally using npm:

```
npm install
```

## Usage

After installing npm packages, the application will be invoked by using the following command:

```
npm run develop
```

#### Heroku Deployment

[Click me to see app!](https://book-search-mern.onrender.com/)

- Create heroku app

  ```
  heroku create
  ```

- Create database on MongoDB Atlas:

  ```
  Cluster ➡️ Collections ➡️ Create Database
  ```

- Change Heroku setting

  ```
  Config Vars ➡️ KEY: MONGODB_URI ➡️ VALUE: (from Cluster connect, change password and database name)
  ```

- Git push
  ```
  git push heroku main
  heroku open
  ```
  
## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) <br>
This project is licensed under MIT, for more information please visit [this website](https://opensource.org/licenses/MIT)

## Contribution

Made by Wenwen Tian

## Questions?

Please feel free to contact me if you need any further information:

- [Email](mailto:ruochenliu155@gmail.com)
- [Github Profile](https://github.com/mason66xue)
