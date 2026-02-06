
🚀 TechHerPath – Full-Stack CRUD Resource App
📌 Project Overview

TechHerPath is a full-stack CRUD web application that allows users to create, view, update, and delete learning resources.
The project was built as part of my backend and full-stack learning journey to understand how real applications connect a frontend, API, and database.

🛠️ Tech Stack

Frontend: HTML, CSS (responsive design), JavaScript (Fetch API)

Backend: Node.js, Express.js

Database: SQL Server

Tools: VS Code, GitHub, Postman

Architecture: RESTful API

⚙️ Features

View all resources stored in the database

Add new resources via a form

Edit existing resources

Delete resources with confirmation

Responsive (mobile-friendly) UI

Backend API connected to SQL Server

Real database CRUD operations

🔗 API Endpoints
Method	Endpoint	Description
GET	/api/resources	Fetch all resources
POST	/api/resources	Add a new resource
PUT	/api/resources/:id	Update a resource
DELETE	/api/resources/:id	Delete a resource
🧠 Key Learnings

Building REST APIs using Express.js

Connecting Node.js to SQL Server

Handling API responses on the frontend

Understanding JavaScript data structures (arrays vs objects)

Debugging real-world errors

Using fetch, JSON, and async logic correctly

Writing cleaner, more structured frontend code

🐛 Challenges & Debugging

One major challenge was handling API responses correctly.
Calling .forEach() on the wrong data structure caused runtime errors. I resolved this by:

Logging the API response

Understanding the response shape

Ensuring .forEach() was only called on arrays

Other challenges included:

Environment variables exposure

Database connection issues

Missing fields causing null values

UI not updating correctly after CRUD actions

Each issue strengthened my debugging and problem-solving skills.

🌱 Future Improvements

Add category filtering

Improve UI styling

Deploy the application online

Add authentication

Write automated tests

✨ Reflection

This project reinforced that learning to code is not about avoiding errors, but about understanding and fixing them.
Debugging was a key part of my growth during this build.
