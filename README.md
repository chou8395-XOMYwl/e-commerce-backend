# E-commerce Back End 
Built the back end for an e-commerce site taking working Express.js API and configuring it to use Sequelize to interact with a MySQL database.

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

## Install
To install, git clone respository and intall packages with the 'npm i' command. 

NPM Install sequelize, and MYSQL2 and add an .env file with credentials added.

.env file should have: DB_NAME, DB_USER, DB_PW.

## Video Walkthrough
https://drive.google.com/file/d/1rsyOr1tExIPFB6B__zW4o-_krdnOWk6H/view

## Github Repo
https://github.com/chou8395-XOMYwl/e-commerce-backend.git