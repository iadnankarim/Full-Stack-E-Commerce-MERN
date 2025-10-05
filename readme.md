# 🛒 Full-Stack E-Commerce Web Application (MERN)

A complete **MERN Stack E-Commerce Platform** with an integrated **Admin Dashboard**.  
This project enables customers to browse products, manage carts, and place orders — while admins can manage products, orders, and inventory in real time.  
It’s built using **React.js**, **Node.js**, **Express.js**, **MongoDB**, and **Cloudinary** for image storage. Payments are integrated with **Stripe** for secure checkout.

---

## 🚀 Features

### 🧑‍💻 User Side

- 🔐 User Authentication (Register / Login with JWT)
- 🛍️ Product Listing by Category and Subcategory
- 🧾 Product Details Page with Multiple Sizes and Images
- 🛒 Add to Cart, Update Quantity, and Remove Items
- 💳 Checkout with Stripe or Cash on Delivery (COD)
- 🧾 Order History & Payment Verification
- 🔄 Real-time Cart Synchronization with Backend

### ⚙️ Admin Panel

- 🔑 Secure Admin Login (Environment-protected credentials)
- ➕ Add, Update, and Delete Products
- 📦 Manage Orders & Update Delivery Status
- 🧠 Product Image Upload via **Cloudinary**
- 📊 Dashboard Navigation (Add Items, List Items, View Orders)
- 💬 Toast Notifications for User and Admin Interactions

---

## 🧩 Tech Stack

**Frontend:**

- ⚛️ React.js
- 🎨 Tailwind CSS
- 🔔 React Toastify
- 🔗 Axios
- 🌐 React Router DOM

**Backend:**

- 🟢 Node.js
- ⚙️ Express.js
- 🍃 MongoDB with Mongoose
- ☁️ Cloudinary for image hosting
- 💳 Stripe for payments
- 🔒 JWT for Authentication
- 🔐 bcrypt for Password Hashing
- 🌍 dotenv for Environment Variables
- 🔄 CORS enabled for cross-origin API access

---

PORT=4000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
ADMIN_EMAIL=your_admin_email
ADMIN_PASSWORD=your_admin_password

## 💳 Payment Integration (Stripe)

- Integrated **Stripe Checkout** for secure and seamless payments.
- Supports **payment success** and **failure verification** routes.
- **Order status** automatically updates upon successful payment.

---

## ☁️ Image Management

- Product images are **uploaded via Cloudinary** for efficient storage.
- Supports **multiple image uploads** for each product.
- **Image URLs** are stored in MongoDB for fast and reliable access.

---

## 🧾 Authentication

- Secure **JWT-based authentication system** for users and admins.
- Passwords are **hashed using bcrypt** for enhanced security.
- **Admin access** is protected through **environment variables**.
