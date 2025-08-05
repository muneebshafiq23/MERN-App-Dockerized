# MERN Todo App
A full-stack Todo application built with the **MERN stack** (MongoDB, Express.js, React, Node.js). This app lets users manage daily tasks with a clean and intuitive UI, persistent storage, and RESTful API integration.

## Features
- Add, update, delete todos
- Persistent data storage with MongoDB
- Real-time updates using REST APIs
- Clean and responsive React frontend
- Express.js & Node.js backend API
- Basic error handling and validation

## Project Structure
 ````` 
mern-todo-app/
│
├── backend/ # Express & Node.js API
│ ├── models/
│ ├── routes/
│ └── server.js
│
├── frontend/ # React application
│ ├── src/
│ └── public/
│
└── README.md
`````
## Tech Stack
- **Frontend**: React, HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (with Mongoose)
- **Version Control**: Git & GitHub

## How to run locally
### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/mern-todo-app.git
cd mern-todo-app
```
### 2. Setup Server (Backend) 
```bash
cd backend
npm install
# Add your MongoDB URI to .env as:
# MONGO_URI=your_mongodb_connection_string
npm start
```
### 3. Setup Client (Frontend)
```bash
cd frontend
npm install
npm start
```
The app will run on: http://localhost:3000
> Make sure MongoDB is running locally or provide a MongoDB Atlas URI in your .env.

## Environment Variables
Create a .env file in the backend/ folder with:
```bash
MONGO_URI=your_mongodb_atlas_connection_string
PORT=5000
```
## Screenshots
<img width="1920" height="842" alt="Screenshot (364)" src="https://github.com/user-attachments/assets/c916585d-8429-4b01-b72f-ba4c828a4961" />

## Author
Faiza Maqsood 
[GitHub Profile](https://github.com/FaizaMaqsood)

## License
This project is open-source and free to use.


