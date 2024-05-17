# E-Commerce Platform

## Description

This project is the back end for an e-commerce site. It provides Express.js API to use Sequelize to interact with a PostgreSQL database.

## Table of Contents 

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Review](#review)

## Installation

To clone and run this repository you'll need Git, PostgreSQL and Node.js (which comes with npm) installed on your computer. 

Fill in database name, your PostgreSQL username, and your PostgreSQL password in the environment varible file to set up the connection to database. 

In command line, install dependencies 

```npm i```

Go into the db folder

```cd db```

Connect to PostgreSQL 

```psql -U postgres```

Create database and exit
```
\i schema.sql
\q
```
Seed the database with test data
```
cd ..
npm run seed
```

## Usage

To invoke the application enter```npm start```.The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia:

![In Insomnia, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](./Assets/13-orm-homework-demo-01.gif)

## Features

* GET/POST routes for all categories, all products, and all tags 
* GET/PUT/DELETE routes for a single category, a single product, and a single tag 

## Review

* A walkthrough demo video.

* The URL of the GitHub repository: https://github.com/Saraz-Git/e-commerce-platform