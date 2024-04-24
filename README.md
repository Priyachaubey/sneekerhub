neakerHub is an e-commerce platform specializing in sneakers. This repository contains the codebase for both the frontend and backend of the website.

Technologies Used
Frontend:
HTML
CSS
JavaScript
Backend:
Node.js
Express.js
Database:
SQL (MySQL)
Installation
Clone the repository:
bash

Navigate to the project directory:
bash
Copy code
cd SneakerHub
Install dependencies:
bash
Copy code
npm install
Set up the database:
Create a MySQL database named sneakerhub.
Import the SQL schema from database/schema.sql.
Configure environment variables:
Create a .env file in the root directory.
Add the following variables:
makefile
Copy code
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=password
DB_DATABASE=sneakerhub
Start the server:
bash
Copy code
npm start
Folder Structure
frontend/: Contains all frontend code.
backend/: Contains all backend code.
database/: Contains SQL schema and migrations.
Usage
Access the website by navigating to http://localhost:3000 in your browser.
Contributing
Fork the repository.
Create a new branch (git checkout -b feature/awesome-feature).
Make your changes.
Commit your changes (git commit -am 'Add awesome feature').
Push to the branch (git push origin feature/awesome-feature).
Create a new Pull Request.

Authors
Priya Chaubey
