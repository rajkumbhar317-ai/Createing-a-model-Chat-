# Createing-a-model-Chat-
# WhatsApp Chat CRUD Application

A simple chat application built using Node.js, Express.js, MongoDB, Mongoose, and EJS.

## Features

* View all chats
* Create a new chat
* Edit existing messages
* Update chat messages
* Store chat data in MongoDB
* User-friendly interface using EJS templates

## Technologies Used

* Node.js
* Express.js
* MongoDB
* Mongoose
* EJS
* Method Override

## Project Structure

├── models/
│   └── chat.js
├── views/
│   ├── index.ejs
│   ├── new.ejs
│   └── edit.ejs
├── public/
├── app.js
├── package.json
└── README.md

## Installation

1. Clone the repository

git clone <repository-url>

2. Install dependencies

npm install

3. Start MongoDB

mongod

4. Run the application

node app.js

5. Open your browser

http://localhost:8080/chats

## Routes

GET /chats - View all chats

GET /chats/new - Create a new chat

POST /chats - Save a new chat

GET /chats/:id/edit - Edit a chat

PUT /chats/:id - Update a chat

## Author

Raj Kumbhar
Java Full Stack Developer
