📚 Book Inventory Management System
A simple yet effective full-stack web application to manage a library or bookstore’s book inventory. It includes user authentication and full CRUD operations for managing book details like title, author, genre, and publication year.

Whether you're a student building projects, a small bookstore owner, or just learning MERN stack development, this app provides a clean and practical template for inventory systems.

🚀 Features
🔐 Secure User Authentication
Users can register and login. Passwords are hashed using bcrypt for security.

📝 Book Management (CRUD)
Users can add, view, update, and delete books with details like title, author, genre, and year.

🌐 RESTful APIs
Clean and modular Express.js routes for authentication and books.

🖥️ Responsive UI
Neatly styled pages for login/register and dashboard built using vanilla HTML/CSS/JS.

📦 MongoDB Integration
All data is stored in a NoSQL MongoDB database using mongoose.

🛠️ Technology Stack
Frontend
HTML5 & CSS3

JavaScript (Vanilla)

Backend
Node.js

Express.js

Database
MongoDB (with Mongoose ODM)

Tools & Libraries
bcrypt – password hashing

JWT – token-based user authentication

nodemon – live reload during development

Postman – API testing

VS Code – development

📁 Project Structure
pgsql
Copy
Edit
book-inventory-manager/
│
├── server.js                 # Main server file
├── models/
│   ├── User.js              # User schema
│   └── Book.js              # Book schema
├── routes/
│   ├── auth.js              # Auth APIs
│   └── books.js             # Book CRUD APIs
├── public/
│   ├── index.html           # Login/Register page
│   └── dashboard.html       # Book dashboard with CRUD


📚 Book Schema Fields
js
Copy
Edit
{
  title: String,
  author: String,
  genre: String,
  publishedYear: Number
}
🔐 Authentication
JWT is used for secure login sessions.

Passwords are hashed before saving using bcrypt.

Token is stored in localStorage on the frontend.

✨ What I Learned
How to set up and structure a MERN stack application.

How to create user login and register functionality securely.

How to implement CRUD operations using MongoDB.

How to build a clean UI using HTML/CSS and connect it to backend logic.

Error handling and testing API routes using Postman.

📦 Future Improvements
Add update functionality in the dashboard UI.

Add pagination or search for large inventories.

Implement role-based access (admin vs user).

Improve UI using frameworks like Bootstrap or React.