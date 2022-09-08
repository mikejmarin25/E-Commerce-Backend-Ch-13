# E-Commerce-Backend-Ch-13

## User Story
- AS A manager at an internet retail company
- I WANT a back end for my e-commerce website that uses the latest technologies
- SO THAT my company can compete with other e-commerce companies


## Acceptance Criteria
- GIVEN a functional Express.js API
- WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
- THEN I am able to connect to a database using Sequelize
- WHEN I enter schema and seed commands
- THEN a development database is created and is seeded with test data
- WHEN I enter the command to invoke the application
- THEN my server is started and the Sequelize models are synced to the MySQL database
- WHEN I open API GET routes in Insomnia for categories, products, or tags
- THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia
- THEN I am able to successfully create, update, and delete data in my database

## Brief Description
E-commerce backend:
- Connects routes to different API endpoints to modify database information
- Implements GetAll, GetById, Update, Delete, Add functionality
- Uses the following NPM tools: dotenv, sequelize, express, mysql2

# Screenshots of Application and Endpoints 

### Starting up the application
<img width="1161" alt="Screen Shot 2022-09-07 at 22 49 00" src="https://user-images.githubusercontent.com/105763252/189023321-e040f728-538c-4d21-be6c-f48a0e642c82.png">

### API endpoints 
<img width="1116" alt="Screen Shot 2022-09-07 at 22 47 35" src="https://user-images.githubusercontent.com/105763252/189023371-7a5f49ac-7271-44e8-b5aa-af5b67558288.png">

### Code Sample for one of the Get Requests
<img width="776" alt="Screen Shot 2022-09-07 at 22 48 07" src="https://user-images.githubusercontent.com/105763252/189023407-7b35e5c1-cca0-4674-ac31-13d8fdaf7f40.png">

## Git Hub Repository
https://github.com/mikejmarin25/E-Commerce-Backend-Ch-13/
