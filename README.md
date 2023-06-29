E-commerce Backend
Description
This is the backend for an e-commerce application. It provides the necessary API routes to manage categories, products, and tags. The backend is built with Express.js and uses Sequelize as the ORM to interact with the MySQL database. It offers various endpoints to perform CRUD operations on the database.

Note: I apologize for the lack of Git commits in this repository. Due to unforeseen issues with the initial repository, I were instructed to create a new repository specifically for the purpose of this assignment. 

Installation
To run the application locally, you need to have Node.js and MySQL installed on your machine. Follow these steps to get started:

Clone the repository: git clone git@github.com:YourUsername/E-commerce-Backend.git
Navigate to the project directory: cd E-commerce-Backend
Install the dependencies: npm install
Set up the database:
Create a .env file based on the .env.example file and provide your MySQL credentials.
Run the database schema creation script from the MySQL shell or an SQL GUI tool.
Optionally, seed the database with initial data by running the appropriate command.
Start the server: npm start
Usage
Once the server is running, you can use an API testing tool like Insomnia or Postman to interact with the API endpoints. The base URL for the API is http://localhost:4005/api. The available routes include:

