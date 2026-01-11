# PRODUCTR - MERN Product Management System

Productr turns basic product listing into a secure, scalable full-stack dashboard with OTP login, JWT auth, protected routes, and full CRUD with image support.

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
<img width="1356" height="631" alt="image" src="https://github.com/user-attachments/assets/ee98ec68-88d0-4f63-b04c-d20bd9d3736d" />

**📩 OTP Verification**
<img width="1359" height="619" alt="image" src="https://github.com/user-attachments/assets/89e30a5b-6507-48a5-b556-2560235a2a56" />

**🏠 Home – Published Products**
<img width="1280" height="620" alt="image" src="https://github.com/user-attachments/assets/defb667f-99bc-4bd7-923f-bcfe20218a0e" />

**🏠 Home – Unpublished Products** 
<img width="1322" height="668" alt="image" src="https://github.com/user-attachments/assets/5a7b9b5e-ebb6-475b-a2df-e9cb10189b5a" />
)
**➕ Add Product**
<img width="1350" height="615" alt="image" src="https://github.com/user-attachments/assets/28f60d79-77bf-499a-ac2f-a1667dbec591" />

**✏ Edit Product**
<img width="1347" height="622" alt="image" src="https://github.com/user-attachments/assets/a21998db-6446-40f2-9a9c-19ec8666c67f" />

**🗑 Delete Product**
<img width="1349" height="630" alt="image" src="https://github.com/user-attachments/assets/739da1c6-6761-4e19-9d99-12cb9c312e48" />



**🚪 Logout**
<img width="171" height="161" alt="image" src="https://github.com/user-attachments/assets/01e5ff9c-07c4-4250-bf6b-2693014a1b14" />

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
## 🙌 My Self
Also, I have built multiple MERN/React full-stack applications similar to this assignment.
You can check more of my projects on my GitHub profile here:
👉 https://github.com/khandanisheth


## 📜 License
Free to use for learning & personal projects.
