Blog Page

Overview

This is a simple blog web application built with Node.js, Express.js, MongoDB (Mongoose), and EJS for templating. The app allows users to create, read, and delete blog posts.

Features

View all blogs

![image](https://github.com/user-attachments/assets/2e04da0f-9f0d-4df8-a8c1-3b6397f5a3ad)


View individual blog details

![image](https://github.com/user-attachments/assets/9c6a10d1-e79c-49ad-a7bb-6f7c855a1bdd)

Create a new blog post

![image](https://github.com/user-attachments/assets/8ce7a831-611c-4772-b8ca-6fa642828aa2)

Delete blog posts

Uses MongoDB Atlas for data storage

![image](https://github.com/user-attachments/assets/608e4832-af97-42fb-924a-5c6bfef5e414)

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

