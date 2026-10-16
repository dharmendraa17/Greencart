# 🛒 GreenCart – Online Grocery Store

GreenCart is a full-stack **MERN-based online grocery shopping application** that provides a simple and user-friendly platform for browsing grocery products, managing a shopping cart, placing orders, and making online payments.

The project includes both a **customer-facing frontend** and a **backend API** for authentication, products, cart, addresses, and orders.

## 🌐 Live Demo

**Frontend:**  
https://greencart-frontend-ashy-kappa.vercel.app/

**GitHub Repository:**  
https://github.com/dharmendraa17/Greencart

---

## ✨ Features

### 👤 User Features

- 🔐 User Registration & Login
- 🔑 Authentication using JWT and Cookies
- 🛍️ Browse grocery products
- 🔎 Search and explore products
- 🗂️ Product categories
- 🛒 Add products to cart
- ➕ Increase/decrease product quantity
- ❌ Remove products from cart
- 📍 Add and manage delivery addresses
- 📦 Place grocery orders
- 💳 Online payment integration
- 💵 Cash on Delivery
- 📋 View order history
- 👤 User account management

### 🏪 Seller Features

- 🔐 Seller authentication
- ➕ Add new products
- ✏️ Manage products
- 🗑️ Delete products
- 📦 View customer orders
- 💰 Check order/payment information
- 🖼️ Product image management

---

## 🛠️ Tech Stack

### Frontend

- React.js
- Vite
- JavaScript
- HTML5
- CSS3
- Axios
- React Router

### Backend

- Node.js
- Express.js
- REST API
- JWT Authentication
- Cookies

### Database

- MongoDB
- Mongoose

### Other Technologies

- Cloudinary – Product image storage
- Razorpay – Online payment integration
- Git & GitHub – Version control
- Vercel – Deployment

---

## 📂 Project Structure

```text
GreenCart/
│
├── Frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── Backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── server.js
│   ├── package.json
│   └── ...
│
├── .gitignore
└── README.md
```

---

## 🔄 Application Flow

```text
User
  │
  ▼
React Frontend
  │
  ▼
Axios / REST API
  │
  ▼
Node.js + Express.js
  │
  ├── Authentication
  ├── Products
  ├── Cart
  ├── Address
  └── Orders
  │
  ▼
MongoDB
```

---

## 🚀 Getting Started

Follow these steps to run GreenCart locally.

### 1. Clone the Repository

```bash
git clone https://github.com/dharmendraa17/Greencart.git
```

### 2. Open the Project

```bash
cd Greencart
```

---

## 🖥️ Run Frontend

```bash
cd Frontend
npm install
npm run dev
```

The frontend will start using Vite.

---

## ⚙️ Run Backend

Open another terminal:

```bash
cd Backend
npm install
npm start
```

If your backend uses a development script:

```bash
npm run dev
```

---

## 🔐 Environment Variables

Create a `.env` file inside the **Backend** folder.

Example:

```env
PORT=4000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
```

For the frontend, create a `.env` file if required:

```env
VITE_BACKEND_URL=your_backend_url
VITE_RAZORPAY_KEY_ID=your_razorpay_key_id
```

> ⚠️ Never upload your `.env` file or API keys to GitHub.

---

## 💳 Payment Integration

GreenCart supports online payment using **Razorpay** along with Cash on Delivery.

Payment flow:

```text
Customer
   ↓
Checkout
   ↓
Select Payment Method
   ↓
Razorpay / COD
   ↓
Order Created
   ↓
Payment Verification
   ↓
Order Confirmation
```

---

## 🔒 Authentication

GreenCart uses **JWT-based authentication** to protect user and seller routes.

Authentication flow:

```text
Login/Register
      ↓
JWT Token
      ↓
HTTP Cookie
      ↓
Protected API
      ↓
Authenticated User
```

---

## 🗄️ Database

The application uses **MongoDB** with **Mongoose** for database operations.

Main data handled by the backend includes:

- Users
- Sellers
- Products
- Cart
- Addresses
- Orders

---

## ☁️ Deployment

The frontend is deployed using **Vercel**.

Live Application:

https://greencart-three-alpha.vercel.app/

The backend can be deployed separately using a Node.js-compatible hosting platform.

---

## 📸 Screens / Modules

### Customer Side

- 🏠 Home
- 🛍️ Products
- 🔎 Product Search
- 🛒 Shopping Cart
- 📍 Address
- 💳 Checkout
- 📦 My Orders
- 🔐 Login / Signup

### Seller Side

- 🔐 Seller Login
- 📊 Seller Dashboard
- ➕ Add Product
- 🛍️ Manage Products
- 📦 Manage Orders

---

## 🎯 Project Objective

The main objective of GreenCart is to build a practical full-stack e-commerce application while implementing real-world concepts such as:

- Frontend and backend integration
- REST API development
- Authentication and authorization
- Database management
- Shopping cart functionality
- Order management
- Payment integration
- Cloud image storage
- Production deployment

---

## 📚 What I Learned

While developing GreenCart, I gained practical experience in:

- React component development
- REST API creation
- Express.js backend development
- MongoDB and Mongoose
- JWT authentication
- Cookies and protected routes
- API integration using Axios
- Payment gateway integration
- Cloudinary integration
- Git and GitHub
- Frontend and backend deployment
- Debugging production issues

---

## 🔮 Future Improvements

Some planned improvements include:

- 📱 Improve mobile responsiveness
- 🔔 Order notifications
- 📍 Order tracking
- ⭐ Product reviews and ratings
- ❤️ Wishlist functionality
- 🔎 Advanced product filtering
- 📊 Advanced seller analytics
- 🧾 Invoice generation
- 📧 Email notifications

---

## 👨‍💻 Developer

**Dharmendra Sahu**

B.Sc. Computer Science Graduate | Full Stack Developer

### Skills

`JavaScript` `React.js` `Node.js` `Express.js` `MongoDB` `Core Java` `SQL` `Git` `GitHub`

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

**Made with ❤️ using the MERN Stack**
