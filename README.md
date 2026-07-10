# 📈 SB Stocks - Full Stack Stock Trading Platform

![React](https://img.shields.io/badge/React-19-blue)
![NodeJS](https://img.shields.io/badge/Node.js-22-green)
![Express](https://img.shields.io/badge/Express-5-lightgrey)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-green)
![JWT](https://img.shields.io/badge/JWT-Authentication-red)
![License](https://img.shields.io/badge/License-MIT-blue)
https://sb-stocks-app.vercel.app/
---

# 📖 Overview

SB Stocks is a full-stack MERN web application that simulates a real-world stock trading platform.

Users can:

- Register/Login securely
- Buy & Sell Stocks
- Track Portfolio
- View Dashboard Analytics
- Monitor Transactions
- Search Stocks
- View Market Data

The project follows modern MERN architecture using React, Express, MongoDB Atlas, JWT Authentication, MVC Architecture, and REST APIs.
<img width="1920" height="1080" alt="landing_pg1" src="https://github.com/user-attachments/assets/90578cbc-30ff-4b2d-9941-aa381103b575" />
<img width="1920" height="1080" alt="landing_pg2" src="https://github.com/user-attachments/assets/e5401fbe-ed11-4e11-9895-4b72b9e720c2" />

---

# ✨ Features

## Authentication

- User Registration
- User Login
- JWT Authentication
- Password Encryption (bcrypt)
- Protected Routes
<img width="1920" height="1080" alt="login_pg" src="https://github.com/user-attachments/assets/9ca65575-79a1-4e00-b8dd-fb7612a17f9a" />
<img width="1920" height="1080" alt="register_pg" src="https://github.com/user-attachments/assets/e3994bd0-a270-40d4-a73a-4d37fe163a61" />

---

## Dashboard

- Portfolio Overview
- Current Balance
- Total Investment
- Profit/Loss
- Recent Transactions
- Recent Orders
- Trending Stocks
- Market Overview
<img width="1920" height="1080" alt="dashboard" src="https://github.com/user-attachments/assets/972efc88-c7b2-4258-bea2-d6a19e8f1522" />

---

## Stock Module

- Stock Listing
- Search Stocks
- Pagination
- Sorting
- Filtering
- Sector Filter
- Market Cap Filter
- Admin CRUD Operations
<img width="1920" height="1080" alt="profile" src="https://github.com/user-attachments/assets/4176bd70-47a3-4484-8dca-d61c7098ee97" />

---

## Portfolio

- Holdings
- Portfolio Summary
- Investment Value
- Profit/Loss
- Auto Portfolio Creation
<img width="1920" height="1080" alt="portfolio" src="https://github.com/user-attachments/assets/3f5ca525-3d73-4af8-883e-d886cdb4cc1d" />

---

## Trading

- Buy Stocks
- Sell Stocks
- Order Management
- Transaction History
- Ownership Validation
- Balance Validation
<img width="1920" height="1080" alt="charts" src="https://github.com/user-attachments/assets/bd29743b-8541-46bb-975d-f432f1bb6fde" />

---

## Backend

- MVC Architecture
- REST APIs
- MongoDB Atlas
- Mongoose ODM
- JWT Authentication
- Express Middleware
- Centralized Error Handling

---

# 🛠 Tech Stack

## Frontend

- React
- Vite
- TanStack Router
- Context API
- Axios
- CSS

## Backend

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT
- bcrypt
- Morgan
- Helmet
- CORS

---

# 📂 Project Structure

```
StockTradingApp
│
├── server
│   ├── config
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── services
│   ├── utils
│   └── server.js
│
├── src
│   ├── components
│   ├── context
│   ├── hooks
│   ├── routes
│   ├── services
│   └── utils
│
├── README.md
├── package.json
└── vite.config.ts
```

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/StockTradingApp.git
```

---

## Install Frontend

```bash
npm install
```

---

## Install Backend

```bash
cd server

npm install
```

---

## Environment Variables

Create

```
server/.env
```

Example

```env
PORT=5000

NODE_ENV=development

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

JWT_EXPIRES_IN=7d

CLIENT_URL=http://localhost:8080
```

---

## Start Backend

```bash
cd server

npm run dev
```

---

## Start Frontend

```bash
npm run dev
```

---

# 📸 Screenshots

## Landing Page

(Add Screenshot)

---

## Login

(Add Screenshot)

---

## Register

(Add Screenshot)

---

## Dashboard

(Add Screenshot)

---

## Portfolio

(Add Screenshot)

---

## Stocks

(Add Screenshot)

---

## Transactions

(Add Screenshot)

---

# 📡 API Endpoints

## Authentication

```
POST /api/auth/register

POST /api/auth/login

POST /api/auth/logout
```

---

## Stocks

```
GET /api/stocks

GET /api/stocks/:id

GET /api/stocks/search

POST /api/stocks

PUT /api/stocks/:id

DELETE /api/stocks/:id
```

---

## Portfolio

```
GET /api/portfolio
```

---

## Orders

```
POST /api/orders/buy

POST /api/orders/sell

GET /api/orders

GET /api/orders/:id

DELETE /api/orders/:id
```

---

## Dashboard

```
GET /api/dashboard
```

---

# 🔒 Security

- JWT Authentication
- Password Hashing
- Protected Routes
- Role Based Authorization
- Input Validation
- MongoDB Validation

---

# 🎯 Future Scope

- Watchlist
- Notifications
- Live Stock Prices
- AI Stock Prediction
- Email Notifications
- Dark Mode

---

# 👨‍💻 Author

**Bhuvanesh Jujare**

B.Tech Computer Science Engineering

Annamacharya Institute of Technology & Sciences - TIRUPATI

---

# 📄 License

This project is licensed under the MIT License.
