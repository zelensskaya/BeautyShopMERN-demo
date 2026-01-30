
# BeautyShop – MERN E-Commerce Application

Full-stack e-commerce web application built with the MERN stack.
The project demonstrates a complete online store workflow including product browsing, user authentication, orders, payments, and an admin panel.




## Features

User Features
- User registration and login
- JWT-based authentication
- Browse products with pagination and search
- View product details and reviews
- Add products to cart
- Place orders
- Pay using PayPal
- View order history
- Add product reviews

Admin Features
- Admin dashboard
- Create, edit, and delete products
- Manage users
- View and update orders
- Mark orders as delivered




## Tech Stack

**Frontend:** React, Redux Toolkit + RTK Query, React Router, React Bootstrap, Axios, React Icons, React Toastify

**Backend:** Node.js, Express.js, MongoDB, Mongoose, JWT (JSON Web Token), bcryptjs


## Environment Variables

Create a .env file in the backend directory and add:

```
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PAYPAL_CLIENT_ID=your_paypal_client_id
```


## Run Locally

Clone the project

```bash
  git clone https://link-to-project
  cd beautyshop
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
  cd frontend
  npm install
```

Start the server

```bash
  npm run dev
```

- Backend runs on: http://localhost:5000
- Frontend runs on: http://localhost:3000

## Database Seeding (Optional)

To import sample data:

```bash
  npm run data:import
```

To destroy data:

```bash
  npm run data:destroy
```

## Authentication & Security

- Passwords are hashed using **bcryptjs**
- Authentication is handled using **JWT**
- Protected routes use middleware for authorization
- Admin routes are restricted to admin users only

## Payments

- Integrated with **PayPal Sandbox**
- Supports online payments during checkout
  
## Screenshots

![Screens](https://github.com/zelensskaya/BeautyShopMERN-demo/blob/main/screens.jpg)
