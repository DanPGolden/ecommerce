# E-Commerce Back End

This is a back end portion for an e-commerce site. This application used Express.js API and Sequelize to interact with a MySQL database. It demonstrates the ability to read, update, create, delete products, tags, and categories with influence and relationships on each other from a relational database.

## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [Demonstration](#demonstration)
<br>

## Installation
Installation is a process of installing the dependencies required. Intialize node package manager and then run the following commands:
* npm install mysql2
* npm install sequelize
* npm install dotenv
<br>

## Usage
In order to use the application, first ensure that MySQL is installed.
Then, from the project root folder enter the sql shell and run the following command:
* source db/schema.sql

Exit the sql shell and return to the command line still within your root project folder.
Run the following commands:

* npm run seed
* npm start
<br>

## Demonstration
The following is demonstation of the application in use.  
https://watch.screencastify.com/v/WhWzvsvX3IFGSzzp4m19

![ecommerce example](ecommerce.gif)