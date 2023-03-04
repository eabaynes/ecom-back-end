# Ecommerce Backend

## Description
This is a simple backend for an ecommerce site. It uses Express.js, MySQL, and Sequelize to create a database and API routes for the database.

## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [See it in Action](#see-it-in-action)

## Installation
This project requires Node.js and MySQL. To install the project, clone the repository and run `npm install` in the root directory. Then, create a `.env` file in the root directory and add the following:
- `DB_NAME='ecommerce_db'`
- `DB_USER='your_mysql_username'`
-`DB_PW='your_mysql_password'`

You can then run the schema and seed files to create the database and populate it with test data. To do this, run `mysql -u root -p` and enter your password when prompted. Then, run `source db/schema.sql` and `source db/seeds.sql`. You can then exit MySQL by running `quit`. Alternatively, you may run `npm run seed` to seed the database after exiting MySQL. Finally, run `npm start` to start the server.

## Usage
This project is intended to be used as a backend for an ecommerce site. It uses Express.js to create API routes for the database. The database is created using MySQL and seeded with test data using Sequelize. The API routes can be tested using Insomnia Core. The following routes are available:
- `GET /api/categories`
- `GET /api/categories/:id`
- `GET /api/products`
- `GET /api/products/:id`
- `GET /api/tags`
- `GET /api/tags/:id`
- `POST /api/categories`
- `POST /api/products`
- `POST /api/tags`
- `PUT /api/categories/:id`
- `PUT /api/products/:id`
- `PUT /api/tags/:id`
- `DELETE /api/categories/:id`
- `DELETE /api/products/:id`
- `DELETE /api/tags/:id`

## See it in Action
[Usage Video](https://drive.google.com/file/d/1Qxyn3dY5sB2GteuF8oZnfNQyEWeeG1UR/view)
