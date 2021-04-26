<h1 align="center">E-Commerce Platform || Backend for E-Commerce Web App</h1>
  
<p align="center">
    <img src="https://img.shields.io/github/languages/top/rjhelm/e-commerce-backend"  />
    <img src="https://img.shields.io/github/last-commit/rjhelm/e-commerce-backend" >
</p>
  
<p align="center">
    <img src="https://img.shields.io/badge/Javascript-yellow" />
    <img src="https://img.shields.io/badge/express-purple" />
    <img src="https://img.shields.io/badge/Sequelize-blue"  />
    <img src="https://img.shields.io/badge/mySQL-blue"  />
    <img src="https://img.shields.io/badge/dotenv-green" />
</p>
   
## Description

 Backend for E-Commerce site that uses mysql2, Sequilize, node, and more.
  
![Seeds](https://github.com/rjhelm/ecommerce-platform/blob/main/assets/run-seeeds.PNG)

![Start](https://github.com/rjhelm/ecommerce-platform/blob/main/assets/start-app.PNG)

![Categories](https://github.com/rjhelm/ecommerce-platform/blob/main/assets/categories-example.PNG)

![Products](https://github.com/rjhelm/ecommerce-platform/blob/main/assets/products-example.PNG)

![Tags](https://github.com/rjhelm/ecommerce-platform/blob/main/assets/tags-example.PNG)

[Walkthrough Video](https://drive.google.com/file/d/1HG7tbH1j7O7NuXNJe_eaGoLNQq8rg5zJ/view)
  
## User Story
  
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
  
## Acceptance Criteria
  
``` 
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```
  
## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation
Installation Steps:
  
`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install dotenv`
  
## Usage

`mysql -u root -p`

Enter password when prompted

`source db/schema.sql`

`quit`

`npm run seed`
  
`npm start`
## Contributing
:octocat: [Ryan Helm](https://github.com/rjhelm)

## Questions
Questions are welcome and you can contact me at: 
[email](mailto:ryjhelm@gmail.com) 
[GitHub](https://github.com/rjhelm)<br />
