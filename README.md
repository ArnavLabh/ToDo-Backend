# ToDo Backend

This is the backend API for a ToDo application built using Express.js and MongoDB.

## Features

- User authentication (JWT-based)
- Create, read, update, delete (CRUD) operations for tasks
- CORS and security middleware included

## Technologies

- Node.js
- Express.js
- MongoDB (Mongoose)
- JSON Web Tokens (JWT)

## Setup Instructions

1. Clone the repository:
   git clone https://github.com/ArnavLabh/ToDo-Backend.git
   cd ToDo-Backend

2. Install dependencies:
   npm install

3. Create a `.env` file with the following variables:
   PORT=5000  
   MONGO_URI=your_mongodb_connection_string  
   JWT_SECRET=your_jwt_secret

4. Run the server:
   npm start

Server runs on http://localhost:5000 by default.
