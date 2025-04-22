# E-Commerce full stack app (BitMart) 🛍️

A full-stack e-commerce web application built with modern technologies for frontend, backend, and admin panel management.

## 📁 Project Structure

backend/
frontend/
admin/

## ✨ Features

### 👨‍💼 Admin Panel
- Login authentication
- Add, update, delete products
- View and manage orders
- Sidebar & navbar UI
- Upload product images using Multer + Cloudinary

### 🛒 Frontend
- View product listings with filters
- Add items to cart
- Place orders via Razorpay/Stripe (depending on setup)
- View order history
- Responsive design

### ⚙️ Backend (API)
- RESTful routes for products, users, cart, and orders
- User authentication
- Role-based access (admin, customer)
- MongoDB Atlas integration
- Vercel-compatible for deployment

---

## 🚀 Tech Stack

| Layer     | Tech Stack |
|-----------|------------|
| Frontend  | React, Vite, Tailwind CSS |
| Admin     | React, Tailwind, Axios, Vite |
| Backend   | Node.js, Express, MongoDB, Mongoose |
| Auth      | JWT (JSON Web Token) |
| Storage   | Cloudinary (Image upload), Multer |
| Payment   | Razorpay, Stripe |
| Deployment | Vercel, Render/Heroku (optional) |

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```
git clone https://github.com/your-username/bitmart.git
cd bitmart

cd backend
npm install
cp .env.example .env  # Add your MongoDB URI, Cloudinary keys, JWT secret
npm run dev

cd ../frontend
npm install
npm run dev

cd ../admin
npm install
npm run dev

```
##backend/.env
```
PORT=5000
MONGODB_URI=mongodb+srv://your-db-uri
JWT_SECRET=your-secret
CLOUDINARY_CLOUD_NAME=your-cloud-name
CLOUDINARY_API_KEY=your-api-key
CLOUDINARY_API_SECRET=your-api-secret
RAZORPAY_KEY_ID=your-key-id
RAZORPAY_KEY_SECRET=your-key-secret
STRIPE_SECRET_KEY=your-stripe-secret
```

