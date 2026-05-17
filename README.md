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

API Collection Documentation 
{
  "info": {
    "_postman_id": "37d7694a-69f2-4bbc-b067-16a4684e30c6",
    "name": "Recipes-app API",
    "schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json",
    "_exporter_id": "54466106",
    "_collection_link": "https://go.postman.co/collection/54466106-37d7694a-69f2-4bbc-b067-16a4684e30c6?source=collection_link"
  },
  "item": [
    {
      "name": "GET",
      "request": {
        "method": "GET",
        "header": [],
        "url": {
          "raw": "http://localhost:3000/api/recipes",
          "protocol": "http",
          "host": [
            "localhost"
          ],
          "port": "3000",
          "path": [
            "api",
            "recipes"
          ]
        }
      },
      "response": []
    },
    {
      "name": "POST",
      "request": {
        "method": "POST",
        "header": [],
        "body": {
          "mode": "raw",
          "raw": "{\r\n    \"title\": \"Homestyle Chicken Curry\",\r\n    \"ingredients\": [\r\n        \"Chicken\", \r\n        \"Onions\", \r\n        \"Tomatoes\", \r\n        \"Ginger Garlic Paste\", \r\n        \"Curry Powder\"\r\n    ],\r\n    \"instructions\": \"Sauté onions and paste. Add tomatoes and spices. Cook chicken until tender.\",\r\n    \"prepTimeMinutes\": 45,\r\n    \"servings\": 4\r\n}",
          "options": {
            "raw": {
              "language": "json"
            }
          }
        },
        "url": {
          "raw": "http://localhost:3000/api/recipes",
          "protocol": "http",
          "host": [
            "localhost"
          ],
          "port": "3000",
          "path": [
            "api",
            "recipes"
          ]
        }
      },
      "response": []
    },
    {
      "name": "PATCH",
      "request": {
        "method": "PATCH",
        "header": [],
        "body": {
          "mode": "raw",
          "raw": "{\r\n    \"servings\": 8,\r\n    \"prepTimeMinutes\": 60\r\n}",
          "options": {
            "raw": {
              "language": "json"
            }
          }
        },
        "url": {
          "raw": "http://localhost:3000/api/recipes/6a07669c58c34c086ec831b9",
          "protocol": "http",
          "host": [
            "localhost"
          ],
          "port": "3000",
          "path": [
            "api",
            "recipes",
            "6a07669c58c34c086ec831b9"
          ]
        }
      },
      "response": []
    },
    {
      "name": "DELETE",
      "request": {
        "method": "DELETE",
        "header": [],
        "url": {
          "raw": "http://localhost:3000/api/recipes/6a07669c58c34c086ec831b9",
          "protocol": "http",
          "host": [
            "localhost"
          ],
          "port": "3000",
          "path": [
            "api",
            "recipes",
            "6a07669c58c34c086ec831b9"
          ]
        }
      },
      "response": []
    }
  ]
}