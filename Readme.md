# EasyPay ![EasyPay Logo](./frontend/src/assets/gitAsset.png)

**EasyPay** is a full-stack web application built with the **MERN** stack (MongoDB, Express.js, React.js, Node.js). It allows users to securely send money, request money, add balance, and manage payment transactions efficiently. The platform provides an intuitive interface to organize transactions and gain insights into spending habits.

---

## 🚀 Features  
- **User Authentication**: Register, login, and logout.  
- **Dashboard**: Manage your profile and view transaction history.  
- **Transactions**:  
  - Send/receive money.  
  - Request/accept payments.  
  - Add balance to your account.  
- **Admin Verification**: Verify users after registration (Admin feature).  

---

## 🛠️ Technologies Used  
### **Frontend**  
- React.js (Initialized with Vite)  
- Redux Toolkit for state management  

### **Backend**  
- Node.js & Express.js  

### **Database**  
- MongoDB  

### **Media Management**  
- Cloudinary API  

---

## 🔧 Installation and Setup  
Follow these steps to run SecurePay locally:

### Step 1: Clone the Repository  
```bash
git clone <repository-url>
```

### Step 2: Install Dependencies  
Navigate to the project directories and install required packages:  
```bash
# Install root dependencies
npm install  

# Frontend setup
cd frontend  
npm install  

# Backend setup
cd ../backend  
npm install  
```

### Step 3: Configure Environment Variables  
Create a `.env` file in the root directory and add the following:  
```env
MONGO_URI=<your-mongo-uri>  
JWT_SECRET=<your-jwt-secret>  
CLOUDINARY_NAME=<your-cloudinary-name>  
CLOUDINARY_API_KEY=<your-cloudinary-api-key>  
CLOUDINARY_API_SECRET=<your-cloudinary-api-secret>  
VITE_URL=https://mern-wallet-two.onrender.com  
```

### Step 4: Run the Application  
Navigate to the root directory and start the development server:  
```bash
npm run dev
```

---

## 🌐 Live Demo and Documentation  
- **Live App**: [EasyPay Live](https://drive.google.com/file/d/1jAo6C9wCgPn610k_int0YSRlNUrc-oye/view?usp=drive_link) 

---

## 🎥 Video Explanation  
Watch the [video demo here](---//---).

---

