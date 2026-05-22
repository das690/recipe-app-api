# Recipe Management API

A secure, cloud-connected RESTful API built using Node.js, Express, and MongoDB Atlas, deployed live on Render.

## 🔗 Live Project Links

* **Live API URL:** `https://recipe-app-api-lbl7.onrender.com/api/recipes`
* **API Documentation:** `https://documenter.getpostman.com/view/54466106/2sBXwjwZZf`
* **GitHub Repository:** `https://github.com/das690/recipe-app-api`

---

## 🚀 Endpoints Available

### 1. Get All Recipes
* **Method:** `GET`
* **URL:** `/api/recipes`
* **Response:** `200 OK` (Returns an array of all recipes)

### 2. Create a Recipe
* **Method:** `POST`
* **URL:** `/api/recipes`
* **Body (JSON):**
    ```json
    {
      "title": "Homestyle Chicken Curry",
      "ingredients": ["Chicken", "Onions", "Tomatoes", "Spices"],
      "instructions": "Sauté ingredients and cook chicken until tender.",
      "prepTimeMinutes": 45,
      "servings": 4
    }
<<<<<<< HEAD
    ```
* **Response:** `201 Created`

### 3. Update a Recipe
* **Method:** `PATCH`
* **URL:** `/api/recipes/:id`
* **Response:** `200 OK`

### 4. Delete a Recipe
* **Method:** `DELETE`
* **URL:** `/api/recipes/:id`
* **Response:** `204 No Content`

---

## 🛠️ Tech Stack & Features
* **Backend:** Node.js with Express.js framework.
* **Database:** MongoDB Atlas (Cloud) connected via Mongoose ODM.
* **Security:** Handled environment variables using `dotenv` and kept credentials hidden using `.gitignore`.
* **Deployment:** Automated builds hosted on Render.
=======
  ]
}

LIVE URL : https://recipe-app-api-lbl7.onrender.com/
>>>>>>> c801396f028eb5c14252507bf0b48866cea38502
