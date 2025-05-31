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
---

## 📸 Screenshots
### 🏠 Home Page
![](https://github.com/user-attachments/assets/ad387f3f-c1c2-472c-ba90-d7d2f49f4793)
![Screenshot 2025-05-31 162105](https://github.com/user-attachments/assets/08dd5cee-4285-4d1d-b4e7-3d275fc5531d)
---
### 📦 All Products Page
![Screenshot 2025-05-31 162141](https://github.com/user-attachments/assets/3e81a76d-0701-4e5f-9b09-e48e17a0cc0c)
---
### 🛒 Cart Page
![Screenshot 2025-05-31 162236](https://github.com/user-attachments/assets/483ae791-3191-42c3-8a76-3d072ce8284c)
---
### 🚚 My Orders Page
![Screenshot 2025-05-31 162317](https://github.com/user-attachments/assets/d4813a09-5303-4ef5-86e2-1db0ec366bc3)
---
### 👨🏻‍💻 Admin Dashboard
![Screenshot 2025-05-31 162414](https://github.com/user-attachments/assets/fd81da03-d273-401b-a2b5-76d3eea8c583)
![Screenshot 2025-05-31 162443](https://github.com/user-attachments/assets/e178807d-cc6b-4572-8acb-096242cdb084)
![Screenshot 2025-05-31 162510](https://github.com/user-attachments/assets/89319933-411c-4738-9ba8-46a160e3579f)
---

## 📄 License
This project is licensed under the [MIT License](https://opensource.org/license/mit).





