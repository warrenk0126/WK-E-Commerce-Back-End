# E-Commerce Back-End

This project is a back-end application for an e-commerce site. It uses Express.js API and Sequelize to interact with a MySQL database.

## Description

This application allows the user to view, add, update, and delete categories, products, and tags in an e-commerce database. It uses Node.js and Express.js to create the API, MySQL for the database, and Sequelize as the ORM to run SQL models and queries. The SQL database includes tables for products, categories, tags, and product tags. RESTful API routes are used to make requests and updates from the database. 

## Walkthrough Video

A walkthrough video demonstrating the functionality of the application can be found [here](https://i.imgur.com/mEt4JGV.mp4).

## Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory in the command line and run `npm install` to install the necessary dependencies.
3. Create a `.env` file in the root of the project and add your MySQL user, password, and database name information.
4. Run `npm run seed` to seed data to your database.
5. Run `npm start` to start the server.

## Usage

Once the server is running, you can use Insomnia Core to test the API endpoints. You can view, add, update, and delete categories, products, and tags.

## Technologies Used

- Node.js
- Express.js
- MySQL
- Sequelize
- Dotenv
