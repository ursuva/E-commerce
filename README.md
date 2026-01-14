# 🛒 E-Commerce Website

A feature-rich E-Commerce Website designed to deliver a seamless shopping experience for users while providing robust backend operations for administrators. This project integrates modern technologies to ensure scalability, performance, and security.

---

## 🚀 Features

### 📦 MongoDB & Redis Integration
- MongoDB: Used as the primary database to store user data, product catalogs, orders, and more.
- Redis: Integrated for caching frequently accessed data, improving performance and reducing latency.

### 💳 Stripe Payment Setup
- Secure payment processing with Stripe.
- Supports multiple payment methods, including credit/debit cards and wallets.

### 🔐 Robust Authentication System
- JWT (JSON Web Tokens) for secure authentication.
- Access Tokens for short-term authentication and Refresh Tokens for renewing sessions.
- Built-in password hashing and recovery mechanisms.

### 🧑‍💻 User Signup & Login
- Easy-to-use registration and login features.
- Validations to ensure data integrity and security.

### 🛍 E-Commerce Core Features
#### Product & Category Management
- Dynamic product catalog with options to add, update, or delete products.
- Organized categories for better user experience.

#### Shopping Cart Functionality
- Add/remove products to/from the cart.
- Real-time updates to the cart.

#### Checkout with Stripe
- Comprehensive checkout process with secure payment handling.
- Email notifications sent for successful transactions.

#### Coupon Code System
- Admin-defined promotional codes for discounts.
- Validation of coupon codes during checkout.

### 🛠 Admin Dashboard
- Manage products, orders, users, and analytics.
- Role-based access control for administrators.

### 📊 Sales Analytics
- Gain insights into sales performance, customer behavior, and revenue trends.
- Interactive graphs and charts for visualization.

### 🎨 Design with Tailwind CSS
- Responsive and modern UI designed with Tailwind CSS.
- Mobile-friendly and accessible design elements.

### 🛒 Cart & Checkout Process
- Persistent shopping cart synced with user sessions.
- Smooth and secure checkout flow.

---

## 🛡 Security Features
- Secure data transmission using HTTPS.
- JWT-based authentication to prevent unauthorized access.
- Data sanitization to avoid SQL injection and XSS attacks.
- Password hashing for safe credential storage.

---

## ⚡ Performance Enhancements
### Data Protection
- Encryption of sensitive information like payment data and personal information.
- Regular database backups to prevent data loss.

### Caching with Redis
- Optimized performance by caching frequently accessed data.

---

## 🛠 Technologies Used
- Backend: Node.js, Express.js
- Frontend: Frontend: React, Vite, Tailwind CSS
- Database: MongoDB
- Caching: Redis
- Payments: Stripe API
- Authentication: JWT

---

## Project Links
- [Project Repository](https://github.com/ursuva/E-commerce)


---

## 🚀 Getting Started

### 1. 📦 Clone the Repository

```bash
git clone https://github.com/ursuva/E-commerce.git
cd E-Commerce
```

### 2. ⚙️ Create .env Files

```bash
PORT=5000
MONGO_URI=your_mongo_uri

UPSTASH_REDIS_URL=your_redis_url

ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

STRIPE_SECRET_KEY=your_stripe_secret_key
CLIENT_URL=http://localhost:5173
NODE_ENV=development
```

### 3. 📥 Install Dependencies

```bash
npm install
```

### 4. ▶️ Run the Project

## Start Backend:
```bash
cd backend
npm run dev
```

## Start Frontend:
```bash
cd frontend
npm run dev
```

---


