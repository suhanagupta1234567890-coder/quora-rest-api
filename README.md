# quora-rest-api
Developed a Quora-style post management system using RESTful API architecture with Node.js and Express. Implemented complete CRUD functionality with dynamic routing and EJS templating, focusing on clean backend structure and real-world API design.

Overview

This project is a simple Quora-like post management system built using RESTful APIs. It allows users to create, read, update, and delete posts — similar to how platforms like Quora handle content.

The main goal of this project is to understand CRUD operations, REST API structure, and routing in backend development.

Tech Stack:-

Node.js
Express.js
EJS (for frontend rendering)
HTML / CSS
Method-Override (for PATCH & DELETE requests)

Features

View all posts
Create a new post
View a single post
Edit/update a post
Delete a post

REST API Routes

1. Get all posts
GET /posts
2. Create a new post
GET /posts/new   → form page  
POST /posts      → add new post  
3. Get single post
GET /posts/:id
4. Update a post
GET /posts/:id/edit   → edit form  
PATCH /posts/:id      → update post  
5. Delete a post
DELETE /posts/:id

CRUD Operations Mapping

Operation	Method	Route	Description
Create	POST	/posts	Add new post
Read	GET	/posts	Get all posts
Read One	GET	/posts/:id	Get single post
Update	PATCH	/posts/:id	Update existing post
Delete	DELETE	/posts/:id	Remove post

Project Structure

project-folder/
│── views/
│   ├── index.ejs
│   ├── new.ejs
│   ├── edit.ejs
│   └── show.ejs
│
│── public/
│── app.js
│── package.json

How to Run the Project

Clone the repository
git clone https://github.com/your-username/quora-clone.git
Install dependencies
npm install
Run the server
node app.js
Open in browser
http://localhost:8080/posts

Learning Outcomes

Understanding RESTful API design
Implementing CRUD operations
Handling routes in Express.js
Working with dynamic data using EJS

Future Improvements

Add database (MongoDB)
User authentication
Like & comment feature
Responsive UI

Author
Suhana Gupta.
