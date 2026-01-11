# PRODUCTR - MERN Product Management System

Productr is a full-stack MERN application with image upload, JWT auth, OTP verification, and protected routes.

---


---

## 🚀 Tech Stack

### Frontend (client)
- React (Vite)
- React Router DOM
- Axios
- Bootstrap / Custom CSS
- LocalStorage Auth

### Backend (server)
- Node.js + Express.js
- MongoDB + Mongoose
- Multer (Image Upload)
- Nodemailer (OTP Email)
- JSON Web Token (JWT)
- dotenv

---

## ⚙️ Installation & Setup

### 1️⃣ Clone or Download Project


---

## 📁 Folder Structure
```
PRODUCTR/
├── client/
│   ├── public/
│   │   └── logo.svg
│   ├── src/
│   │   ├── assets/
│   │   │   └── dummy.txt
│   │   ├── components/
│   │   │   ├── Home.jsx
│   │   │   ├── Login.jsx
│   │   │   ├── ProductModal.jsx
│   │   │   ├── Sidebar.jsx
│   │   │   └── Topbar.jsx
│   │   ├── Css/
│   │   │   ├── Home.css
│   │   │   ├── login.css
│   │   │   ├── ProductModal.css
│   │   │   └── Products.css
│   │   ├── pages/
│   │   │   ├── Otp.jsx
│   │   │   ├── Products.jsx
│   │   │   └── ProtectedRoute.jsx
│   │   ├── App.jsx
│   │   ├── index.css
│   │   └── main.jsx
│   ├── .gitignore
│   ├── eslint.config.js
│   ├── index.html
│   ├── package.json
│   ├── package-lock.json
│   └── vite.config.js
├── server/
│   ├── Controllers/
│   │   ├── authController.js
│   │   └── productController.js
│   ├── models/
│   │   ├── OtpStore.js
│   │   └── Product.js
│   ├── routes/
│   │   ├── authRoutes.js
│   │   └── productRoutes.js
│   ├── uploads/
│   │   └── .gitkeep
│   ├── node_modules/
│   ├── .env.example
│   ├── package.json
│   ├── package-lock.json
│   └── server.js
└── README.md
```



###  Install Dependencies
#### ➤ Client (React)
cd client
npm install
npm run dev


#### ➤ Server (Node)
cd server
npm install
npm start



---

## 🔐 Environment Variables

Create a `.env` file in **server** folder:
PORT=5000
MONGO_URI=mongodb://localhost:27017/your__________
EMAIL_USER=your@gmail.com
EMAIL_PASS= EMAIL_PASS



---

## 🧪 API Endpoints

### Auth
| Method | Route            | Description         |
|--------|------------------|---------------------|
| POST   | /send-otp        | Send OTP to email   |
| POST   | /verify-otp      | Verify OTP + Login  |

### Products
| Method | Route             | Description               |
|--------|-------------------|---------------------------|
| POST   | /addproduct       | Add product with images   |
| GET    | /allproduct       | Fetch all products        |
| DELETE | /delete/:id       | Delete product            |

---

## 🛡️ Protected Route (Frontend)
Uses `<ProtectedRoute />` to restrict pages if user not logged in.

Token stored in `localStorage`.

---

## 🖼 Image Uploads

**🔑 Login**
![alt text](image.png)
**📩 OTP Verification**
![alt text](image-1.png)
**🏠 Home – Published Products**
![alt text](image-2.png)
**🏠 Home – Unpublished Products** 
![alt text](image-3.png)
**➕ Add Product**
![alt text](image-4.png)
**✏ Edit Product**
![alt text](image-5.png)
**🗑 Delete Product**
![alt text](image-6.png)
**🚪 Logout**
![alt text](image-7.png)


Make sure folder exists.

---

## 🧱 Project Modules

### Client (src)
- `components/` → UI blocks (Home, Login, Sidebar, Topbar)
- `pages/` → Pages routing (Products, OTP, ProtectedRoute)
- `Css/` → Stylesheets
- `App.jsx` → Routes setup
- `main.jsx` → React root

### Server
- `controllers/` → Business logic
- `models/` → Mongo schemas
- `routes/` → Express routes
- `uploads/` → Image storage

---

## ▶ How to Use
1. Open site
2. Enter email → receive OTP
3. Verify OTP → auto login
4. Add, list and delete products

---

## 🎯 Features
✔ OTP Login  
✔ Protected Routes  
✔ Add / View / Delete Products  
✔ Multiple Image Upload  
✔ Clean MERN Architecture  

---

## 🙌 Contribute
Feel free to improve UI, backend validations, edit forms, or add new features.

---

## 📜 License
Free to use for learning & personal projects.
