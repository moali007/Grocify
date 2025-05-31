# 🛒 Grocify – Grocery Delivery Ecommerce Website

Grocify is a full-stack grocery delivery ecommerce platform built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js). It provides a seamless and secure shopping experience for users to browse, search, and purchase groceries online, while also offering an intuitive seller dashboard for managing inventory and orders.

---

## 🚀 Features

### 🛍️ User Features
- **Responsive UI** for all devices
- **Category-based product search**
- **Cart management** and order placement
- **Secure authentication** using JWT
- **Stripe payment integration**
- **Payment verification using Stripe webhooks**

### 🧑‍💼 Seller/Admin Features
- Admin **login with JWT authentication**
- Add, edit, or delete grocery items
- **Manage stock levels**
- View and manage all customer orders

---

## 🛠️ Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Payments**: Stripe + Stripe Webhooks

---

## 🔐 Security Highlights

- JWT-based secure **login/signup system**
- Protected API routes with middleware
- Stripe **webhook verification** for payment validation
- **Environment variables** used for sensitive data (e.g., API keys)

---
## 📦 Installation

### Prerequisites
- Node.js & npm
- MongoDB
- Stripe account (for payment integration)
- Cloudinary account

### 1. Clone the Repository
```bash
git clone https://github.com/moali007/grocify.git
cd grocify
```

### 2. Set Up Environment Variables
Create `.env` files in both the root and client directories and add your environment-specific variables

Example for backend `.env`:
```bash
JWT_SECRET=""
#Admin Credentials
SELLER_EMAIL = ""
SELLER_PASSWORD = ""

# MongoDB Setup
MONGODB_URI = ""

# Cloudinary
CLOUDINARY_CLOUD_NAME = ''
CLOUDINARY_API_KEY = ''
CLOUDINARY_API_SECRET = ''

# Stripe Setup
STRIPE_PUBLISHABLE_KEY = ''
STRIPE_SECRET_KEY = ''
STRIPE_WEBHOOK_SECRET = ''
```
Example for frontend `.env`:
```bash
VITE_CURRENCY = '₹'
VITE_BACKEND_URL = ""
```
### 3. Install Dependencies
```bash
# Backend
cd server
npm install

# Frontend
cd client
npm install
```
### 4. Run the Application
```bash
# Backend
cd server
npm run start

# Frontend (in a separate terminal)
cd client
npm run dev
```

### 📁 Project Structure
```bash
grocify/
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── utils/
├── client/
│   ├── components/
│   ├── pages/
│   └── context/
└── .env
```

### 📸 Screenshots
