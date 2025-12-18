Split App – Expense Sharing Application

A application that helps users split group expenses, track balances, and settle dues.

##  Live Demo
Frontend: https://split-app-ayush.onrender.com/
Backend API: https://split-app-ay.onrender.com  

## ✨ Features

- User authentication (register & login)
- Create and manage groups
- Add expenses and split costs among group members
- Track who owes whom in real time
- View payables and receivables dashboard
- Settle balances partially or fully
- Responsive UI for desktop and mobile

##  Tech Stack

**Frontend**
- React (Vite)
- Axios
- CSS / Tailwind (if used)

**Backend**
- Node.js
- Express.js
- MongoDB (MongoDB Atlas)
- JWT for authentication

**Deployment**
- Render (Backend + Frontend)
- GitHub for version control

##  Project Structure

```text
Split-App-Project/
├── backend/
│   ├── src/
│   │   ├── routes/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── app.js
│   │   └── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   ├── components/
│   │   └── services/
│   └── package.json
│
└── README.md
```


##  Environment Variables

### Backend
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### Frontend
```
VITE_API_URL=https://split-app-ay.onrender.com
```

## 🧪 Run Locally

### 1. Clone the repository

### 2. Start backend
```
cd backend
npm install
npm run dev
```

### 3. Start frontend
```
cd frontend
npm install
npm run dev
```
Frontend runs on `http://localhost:5173`

## 🔌 API Endpoints (Sample)

```
- POST /users/register – Register user
- POST /users/login – Login user
- POST /groups – Create group
- POST /expenses – Add expense
- GET /dashboard/:userId – User dashboard
```



