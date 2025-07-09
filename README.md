# Permalist - To-Do List Web App

A simple web-based to-do list application built using **Node.js**, **Express**, **PostgreSQL**, and **EJS**. This app allows users to **add**, **edit**, and **delete** tasks stored in a PostgreSQL database.

---

## Features

- 📝 Add new tasks
- ✏️ Edit existing tasks
- ✅ Mark tasks as complete (delete them)
- 💾 Data is persisted using PostgreSQL
- 🌐 Clean and responsive UI with EJS templates

---

## Tech Stack

- **Backend**: Node.js, Express
- **Frontend**: HTML, EJS
- **Database**: PostgreSQL
- **Templating**: EJS
- **Styling**: CSS (linked in `header.ejs` as `styles/main.css`)

---

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/permalist.git
   cd permalist
   ```
   npm install
   createdb permalist
   createdb permalist
   psql -d permalist -f queries.sql
   const db = new pg.Client({
   user: "postgres",
   host: "localhost",
   database: "permalist",
   password: "your_password",
   port: 5432,
   });
   npm start
   npx nodemon index.js

📁 project-root/
├── index.js # Main server file
├── solution.js # Duplicate of index.js (for reference)
├── queries.sql # PostgreSQL schema and seed data
├── package.json
├── views/
│ ├── index.ejs # Main to-do list page
│ └── partials/
│ ├── header.ejs # HTML <head> and start of <body>
│ └── footer.ejs # Footer and end of </body>
└── public/
└── styles/
└── main.css # (you need to create this if not present)
CREATE TABLE items (
id SERIAL PRIMARY KEY,
title VARCHAR(100) NOT NULL
);

INSERT INTO items (title) VALUES ('Buy milk'), ('Finish homework');

npm install express body-parser ejs pg
npm install --save-dev nodemon
