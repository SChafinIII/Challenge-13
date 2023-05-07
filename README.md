# E-commerce Back End Starter Code

This is a backend e-commerce website using the latest technologies. The website is built with functional Express.js API that connects to a MySQL database using Sequelize.

## User Story

As a manager at an internet retail company, I want a back end for my e-commerce website that uses the latest technologies so that my company can compete with other e-commerce companies.

## Acceptance Criteria

The following acceptance criteria must be met in order for the challenge to be considered complete:

- Given a functional Express.js API
- When I add my database name, MySQL username, and MySQL password to an environment variable file
- Then I am able to connect to a database using Sequelize
- When I enter schema and seed commands
- Then a development database is created and is seeded with test data
- When I enter the command to invoke the application
- Then my server is started and the Sequelize models are synced to the MySQL database
- When I open API GET routes in Insomnia Core for categories, products, or tags
- Then the data for each of these routes is displayed in a formatted JSON
- When I test API POST, PUT, and DELETE routes in Insomnia Core
- Then I am able to successfully create, update, and delete data in my database

## Installation

1. Clone the repository from GitHub.
2. Open the terminal in the root directory of the project.
3. Run `npm install` to install all dependencies.
4. Create a `.env` file based on the `.env.EXAMPLE` file.
5. Add your database name, MySQL username, and MySQL password to the `.env` file.
6. Run `npm run schema` to create the development database.
7. Run `npm run seed` to seed the development database with test data.
8. Run `npm start` to start the server and sync the Sequelize models to the MySQL database.

## Usage

The following routes are available for testing in Insomnia Core:

### GET Routes

- `/api/category` - Get all categories
- `/api/products` - Get all products
- `/api/tags` - Get all tags

### POST Routes

- `/api/categories` - Create a new category
- `/api/products` - Create a new product
- `/api/tags` - Create a new tag

### PUT Routes

- `/api/categories/:id` - Update a category by id
- `/api/products/:id` - Update a product by id
- `/api/tags/:id` - Update a tag by id

### DELETE Routes

- `/api/categories/:id` - Delete a category by id
- `/api/products/:id` - Delete a product by id
- `/api/tags/:id` - Delete a tag by id

All data is sent and received in JSON format.

## Technologies Used

- Express.js
- MySQL
- Sequelize

## License

This project is licensed under the MIT license. See the LICENSE file for more information.