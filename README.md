# Recipe Management API

A robust RESTful API built with Node.js, Express, and Mongoose for managing a digital recipe catalog. This project strictly follows the MVC (Model-View-Controller) design pattern.

## Features
* Complete CRUD functionality (Create, Read, Update, Delete).
* Clean MVC architecture.
* MongoDB integration using Mongoose.
* Built-in data validation and error handling (e.g., catching missing fields, invalid IDs).

## Tech Stack
* **Runtime:** Node.js
* **Framework:** Express.js
* **Database:** MongoDB
* **ODM:** Mongoose

## Installation and Setup
1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Create a `.env` file in the root directory and add your variables:
4. Start the server using `node server.js` (or `nodemon server.js` for development).

## API Endpoints
* `POST /api/recipes` - Create a new recipe
* `GET /api/recipes` - Retrieve all recipes
* `GET /api/recipes/:id` - Retrieve a specific recipe
* `PATCH /api/recipes/:id` - Update a recipe
* `DELETE /api/recipes/:id` - Delete a recipe