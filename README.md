# E-commerce-Back-End

## Description
This project demonstrates an E-Commerce back-end application for an internet retail company built using Node.js, Express, and Sequelize, which connects to a MySQL database.

## Installation
1. Clone the Repository
2. Install Dependencies
    npm install
3. Create a .env file with:
    DB_NAME='your_database_name'
    DB_USER='your_username'
    DB_PW='your_password'
4. Seed the Database
    npm run seed

## Usage
To start the application:
    npm run start
or with nodemon:
    npm run watch
    
API Endpoints

All Products: GET http://localhost:3001/
Product by ID: GET http://localhost:3001/:id
Add Product: POST http://localhost:3001/
json
{
    "product_name": "Sample",
    "price": 19.99,
    "stock": 100,
    "tagIds": [1, 2]
}

Update Product: PUT http://localhost:3001/:id
Delete Product: DELETE http://localhost:3001/:id

![Screenshot 2023-08-23 183231](https://github.com/butlerem/E-commerce-Back-End/assets/130527417/f98541c5-7115-4695-9ce8-dcbd97f39fb6)

## License
This project is licensed under the MIT License.
https://opensource.org/licenses/MIT
![Github license](https://img.shields.io/badge/license-MIT-blue.svg)

## Credits
The starter code is available here:

https://github.com/coding-boot-camp/fantastic-umbrella
 
## Testing
The demonstration video is available here:

https://drive.google.com/file/d/18upACuZXFfZZVDH_F-_bcsbLvcCENVqX/view?usp=sharing

## Questions
Please send any questions to [github/butlerem](https://github.com/butlerem).

🌼
