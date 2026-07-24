# 🛒 MERN Stack E-Commerce Web Application

A full-stack E-Commerce web application developed using the MERN Stack (MongoDB, Express.js, React.js, and Node.js). The project provides a complete online shopping experience with secure authentication, product management, shopping cart, multiple payment options, automated email notifications, and PDF invoice generation.

## ✨ Features

- 👤 User Registration & Login
- 🔐 JWT Authentication & Authorization
- 🛍️ Product Management
- 🛒 Shopping Cart
- 💳 Stripe & Razorpay Payment Integration
- 💵 Cash on Delivery (COD)
- ☁️ Cloudinary Image Upload
- 📧 Order Confirmation Email
- 📄 PDF Invoice Generation
- 👨‍💼 Admin Dashboard
- 📦 Order Management

  ## 🛠️ Tech Stack

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript
- Axios

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Authentication
- JWT
- bcrypt

### Other Tools
- Cloudinary
- Multer
- Nodemailer
- Stripe
- Razorpay
- PDFKit
- Git
- GitHub

## 📁 Project Structure

```text
E-commerce-main/
│
├── admin/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   ├── package.json
└── ...
```

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/your-username/your-repository.git
```

### Install dependencies

Backend

```bash
cd backend
npm install
npm start
```

Frontend

```bash
cd frontend
npm install
npm run dev
```

Admin

```bash
cd admin
npm install
npm run dev
```
## 🔑 Environment Variables

Create a `.env` file inside the backend folder and configure:

- MONGODB_URI
- JWT_SECRET
- CLOUDINARY_CLOUD_NAME
- CLOUDINARY_API_KEY
- CLOUDINARY_SECRET_KEY
- STRIPE_SECRET_KEY
- RAZORPAY_KEY_ID
- RAZORPAY_KEY_SECRET
- EMAIL_USER
- EMAIL_PASS
- ADMIN_EMAIL
- ADMIN_PASSWORD

  ## 👩‍💻 Author

**Gaganpreet Kaur**

- MCA Student
- MERN Stack Developer

GitHub: https://github.com/your-username

LinkedIn: https://www.linkedin.com/in/your-profile
