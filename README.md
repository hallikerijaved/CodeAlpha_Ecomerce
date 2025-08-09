# Cartt - Simple E-commerce Store

A basic e-commerce web application built with Node.js, Express.js, MongoDB, and HTML/CSS/JavaScript frontend.

## Features

- Product listing with details
- Shopping cart
- User registration/login
- Order placement
- Admin product management (optional)

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose

## Getting Started

```bash
git clone https://github.com/hallikerijaved/CodeAlpha_Ecomerce.git
cd cartt
npm install
```

### Run the Server

```bash
npm start
```

Visit `http://localhost:3000` in your browser.

## Folder Structure

```
cartt/
│
├── models/              # Mongoose schemas (e.g. Product, User)
├── public/              # Static assets (CSS, images, etc.)
├── routes/              # Express routes (product, cart, auth)
├── views/               # EJS templates for frontend rendering
├── seeder.js            # Script to insert sample data
├── app.js               # Main Express server
├── package.json         # Node dependencies
└── README.md
```

## Seeder Script

To insert sample product data into MongoDB, run:

```bash
node seeder.js
```

Ensure MongoDB is running locally or provide a correct connection string.

## License

This project is open-source and available for educational and development purposes.
