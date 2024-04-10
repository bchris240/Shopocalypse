Shopocalypse E-commerce Back End
Shopocalypse is an e-commerce back end built using Express.js and Sequelize, allowing businesses to manage their products, categories, and tags efficiently.

Table of Contents
Installation
Usage
API Routes
Walkthrough Video
Contributing
License
Installation
Clone the repository to your local machine:
git clone https://github.com/bchris240/shopocalypse.git

Navigate to the project directory:
cd shopocalypse
Install dependencies:
npm install

Create a .env file in the root directory and add the following environment variables:
DB_NAME=Shopocalypse
DB_USER=root
DB_PASSWORD=your_password
Create your database schema using the provided schema.sql file in the db folder.
Seed your database with test data:
npm run seed

Start the server:
node server.js

Usage
Once the server is running, you can access the API endpoints using tools like Insomnia or Postman. Refer to the API Routes section for details on available endpoints.

API Routes
GET /api/categories: Get all categories.

GET /api/categories/:id: Get a single category by ID.

POST /api/categories: Create a new category.

PUT /api/categories/:id: Update a category by ID.

DELETE /api/categories/:id: Delete a category by ID.

GET /api/products: Get all products.

GET /api/products/:id: Get a single product by ID.

POST /api/products: Create a new product.

PUT /api/products/:id: Update a product by ID.

DELETE /api/products/:id: Delete a product by ID.

GET /api/tags: Get all tags.

GET /api/tags/:id: Get a single tag by ID.

POST /api/tags: Create a new tag.

PUT /api/tags/:id: Update a tag by ID.

DELETE /api/tags/:id: Delete a tag by ID.

Walkthrough Video
Watch Walkthrough Video

Watch the video to see a demonstration of the application's functionality, including database setup, seeding, and API endpoints testing.

Contributing
Contributions are welcome! Please submit any bug fixes or feature enhancements as pull requests.

GitHub Repository
Shopocalypse GitHub Repository

Feel free to clone or fork the repository to experiment with the code.
