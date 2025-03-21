Blog Page

Overview

This is a simple blog web application built with Node.js, Express.js, MongoDB (Mongoose), and EJS for templating. The app allows users to create, read, and delete blog posts.

Features

View all blogs

![image](https://github.com/user-attachments/assets/fd906000-8cf7-4e5c-83b7-eeb37dead470)

View individual blog details
![image](https://github.com/user-attachments/assets/c01d47e7-d987-49ab-98bd-919bcebe3b08)

Create a new blog post
![image](https://github.com/user-attachments/assets/de48e065-3ecc-4802-ba72-74c94f4a970b)

Delete blog posts

Uses MongoDB Atlas for data storage

EJS templating for dynamic pages

Morgan logging middleware

Express.js for handling requests

Technologies Used

Backend: Node.js, Express.js, MongoDB (mongoose)

Frontend: HTML, CSS, EJS (Embedded JavaScript)

Database: MongoDB Atlas

Installation & Setup

Make sure you have the following installed:

Node.js

MongoDB Atlas

Steps

Clone the repository

Install dependencies

Set up MongoDB Atlas connection

Update the dbURI in app.js with your MongoDB connection string.

Run the server

The server will start at http://localhost:3000.

API Routes

Blog Routes

GET /blogs - Fetch all blogs

POST /blogs - Create a new blog

GET /blogs/:id - View a single blog post

DELETE /blogs/:id - Delete a blog post

GET /blogs/create - Render the blog creation form

Project Structure

License

This project is licensed under the MIT License.

Author

Developed by Plamen Draganov.

