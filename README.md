# E-Commerce Back End
## Description
A back-end for an e-commerce site built with Express.js, and PostgreSQL. It provides APIs for managing products, categories, and tags.

## Installation
1. Clone the repository:

git clone https://github.com/yourusername/ecommerce-backend.git
cd ecommerce-backend

2. Install dependencies:

npm install

3. Set up the PostgreSQL database and seed data:

psql -U postgres -d ecommerce_db -f db/schema.sql
npm run seed

4. Create a .env file:

DB_NAME=ecommerce_db
DB_USER=your_postgresql_username
DB_PASSWORD=your_postgresql_password

## Usage

1. Start the server:

npm start

2. Test the API endpoints using Insomnia/Postman for products, categories, and tags.

## Walkthrough Video
https://ooo.mmhmm.app/watch/z_KLCCUTd9yPflML8wjmiQ