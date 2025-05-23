📄 README.md
markdown
Copy
Edit
# Sample Fullstack Project

This is a simple full-stack application for managing products. It includes a frontend built with **React** and a backend using **Express.js** with **MongoDB** as the database.

## 🌐 Features

- List all products
- Add a new product
- Edit existing products
- Delete products
- Input validation on the frontend
- RESTful API integration

---

## 📁 Project Structure

sample_fullstack_project/
│
├── backend/ # Express + MongoDB backend
│ ├── index.js # Main server file
│ └── ... # Other backend files
│
├── frontend/ # React frontend
│ ├── src/
│ │ ├── App.js
│ │ └── App.css
│ └── ...
│
├── README.md
└── package.json # If using a root-level config

yaml
Copy
Edit

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/sample_fullstack_project.git
cd sample_fullstack_project

2. Start the backend
bash
cd backend
npm install
node index.js
Make sure MongoDB is running on mongodb://localhost:27017/shop

3. Start the frontend
bash
cd ../frontend
npm install
npm start

📦 API Endpoints
Method	Endpoint	Description
GET	/products	Get all products
POST	/products	Add new product
PUT	/products/:id	Update product
DELETE	/products/:id	Delete product

🛠 Technologies Used
Frontend: React, HTML, CSS

Backend: Express.js, Node.js

Database: MongoDB with Mongoose

📌 Notes
Be sure to run MongoDB locally or update the connection string in index.js if you're using MongoDB Atlas.

The frontend connects to backend at http://localhost:3000/products — ensure CORS is enabled on the backend.
