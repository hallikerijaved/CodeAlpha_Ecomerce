# 🛒 Simple E-commerce Store

A basic e-commerce website built using **Node.js**, **Express.js**, **MongoDB**, and **HTML/CSS/JavaScript**. It features product listings, a shopping cart, user registration/login, and order processing.

---

## 🚀 Features

- Product Listing Page
- Product Detail Page
- Shopping Cart
- Order Checkout
- User Registration & Login
- Admin Product Seeder

---

## 🧰 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)

---

## 📂 Project Structure

cartt/
├── models/ # Mongoose Models (Product, User, Order)
├── routes/ # Express Routes
├── views/ # HTML Pages (EJS or Static)
├── public/ # Static assets (CSS, JS, images)
├── seeder.js # Script to seed sample products
├── server.js # Main server file
├── package.json
└── .env # Environment variables



---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone <your-repo-url>
cd cartt
2. Install Dependencies
bash
Copy
Edit
npm install
3. Configure MongoDB
Make sure MongoDB is installed and running on your system (default: mongodb://localhost:27017/ecommerce).

You can also use MongoDB Atlas – update .env file:

ini
Copy
Edit
MONGODB_URI=mongodb://localhost:27017/ecommerce
PORT=3000
4. Seed Sample Products
bash
Copy
Edit
node seeder.js
5. Start the Server
bash
Copy
Edit
npm start
The site will be running at: http://localhost:3000

🖼️ Screenshots
You can insert screenshots of your product listing, product detail, cart, and login pages here.

🙋‍♂️ Author
Developed by [Your Name or Team Name]
