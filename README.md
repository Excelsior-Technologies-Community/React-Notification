# 🔔 React Notification System

## Screenshots

### Login Page
<img width="1919" height="999" alt="Screenshot 2025-12-04 192146" src="https://github.com/user-attachments/assets/e2962c6b-c2d3-4907-88ec-a950cc2d65f4" />

<img width="1911" height="977" alt="Screenshot 2025-12-05 173734" src="https://github.com/user-attachments/assets/0ab0bf54-dc46-4e8d-8d3f-9d9f5c149586" />


### Register Page

<img width="1919" height="965" alt="Screenshot 2025-12-05 173936" src="https://github.com/user-attachments/assets/fb0fa5d8-93f9-4a07-81e1-b848c6fd1f2b" />

<img width="1919" height="965" alt="Screenshot 2025-12-05 173936" src="https://github.com/user-attachments/assets/8d6d2ea8-d202-41b5-bf95-6b0c55a39aff" />

<img width="1917" height="976" alt="Screenshot 2025-12-05 173808" src="https://github.com/user-attachments/assets/13007412-51e7-44b6-91b5-99fde1997a0f" />


---

A fully functional **React project** to show notifications using **Toast, Alerts, and Async Notifications**. It includes authentication features and communicates with a backend API.

### Features

- 🔔 **Toast Notifications**
- ⚠️ **Alert Messages**
- 🔄 **Async Notifications** (Loading → Success → Error)
- 🌐 **Real API example** (Login / Register)
- 👤 **Authentication**
  - User Registration API
  - User Login API
  - Bcrypt password hashing
  - JSON Web Tokens (JWT)

This project helps you notify users when:

- API is loading
- Action is successful
- Something goes wrong
- You want to show warnings

---

## 📂 Folder Structure

### Frontend
```
frontend/
│── src/
│   ├── components/
│   │   ├── LoadingButton.jsx
│   ├── pages/
│   │   ├── LoginPage.jsx
│   │   └── Register.jsx
│   ├── App.jsx
│   └── main.jsx
│── index.html
│── package.json
│── vite.config.js
```

### Backend
```
backend/
│── src/
│   ├── controllers/
│   │   ├── authController.js
│   ├── models/
│   │   ├── userModel.js
│   ├── routes/
│   │   ├── authRoutes.js
│   ├── config/
│   │   ├── db.js
│   ├── middleware/
│   │   ├── authMiddleware.js
│   └── app.js
│── .env
│── package.json
```

---

## 🛠️ Tech Stack

**Frontend**
- React + Vite
- Axios
- Custom Toast Component

**Backend**
- Node.js
- Express.js
- MongoDB
- Mongoose
- bcrypt
- JWT authentication

---

## 🚀 Backend Setup

1️⃣ Install Dependencies
```bash
cd backend
npm install
```

2️⃣ Setup Environment File
Create a `.env` file in the backend root:
```env
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_secret_key
```

3️⃣ Start Server
```bash
npm run dev
```

---

## 🖥️ Frontend Setup

1️⃣ Install Dependencies
```bash
cd frontend
npm install
```

2️⃣ Start React App
```bash
npm run dev
```

The app should now be running at `http://localhost:5173` (or the port Vite shows) and connected to your backend APIs.

