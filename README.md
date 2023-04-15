# E-commerce Back End Starter Code

## Description 
In this assignment, we take a look at the back end for an e-commerce website. We configure an Express.js API to use Sequalize to interact with a MySQL database. This project includes starter code which needed editing in order to run correctly. We begin by creating the Schema and Seed data. Next, we launch a server in order to seed the data in a development database. Our goal is to sync the Sequalize models to the MySQL database so we can create, update, and delete data in the database. 

## Acceptance Criteria
- GIVEN a functional Express.js API
- WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
- THEN I am able to connect to a database using Sequelize
- WHEN I enter schema and seed commands
- THEN a development database is created and is seeded with test data
- WHEN I enter the command to invoke the application
- THEN my server is started and the Sequelize models are synced to the MySQL database
- WHEN I open API GET routes in Insomnia Core for categories, products, or tags
- THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
- THEN I am able to successfully create, update, and delete data in my database