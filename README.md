# Parking Slot Management System

## 📌 Overview
A full-stack web and mobile application for seamless parking slot management, allowing users to check real-time parking availability, book slots, and make payments efficiently.

## 🚀 Technologies Used
- **Frontend (Web App):** React.js
- **Mobile App:** React Native (Android)
- **Backend:** Node.js (Express.js)
- **Database:** MySQL
- **Authentication & Security:** JWT Authentication, Role-Based Access Control (RBAC)

## 🎯 Features
- 🔹 **Admin Dashboard:** Manage users, monitor parking slots, and handle transactions.
- 🔹 **Real-Time Slot Tracking:** Live updates on slot availability.
- 🔹 **Booking System:** Users can book parking slots in advance.
- 🔹 **Secure Payments:** Integrated payment gateway.
- 🔹 **Transaction History:** Users can track past bookings and payments.
- 🔹 **Reports & Analytics:** Admins get insights on parking usage.

## 🏗️ Project Structure
```
Parking-Slot-Management-System/
│-- backend/          # Node.js (Express.js) server
│-- frontend/         # React.js Web Admin Dashboard
│-- mobile/           # React Native App
│-- database/         # MySQL Scripts
│-- README.md         # Documentation
```

## ⚙️ Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/parking-slot-management.git
cd parking-slot-management
```

### 2️⃣ Backend Setup
```sh
cd backend
npm install
npm start
```

### 3️⃣ Frontend Setup (Web App)
```sh
cd frontend
npm install
npm start
```

### 4️⃣ Mobile App Setup
```sh
cd mobile
npm install
npx react-native run-android
```

### 5️⃣ Database Setup (MySQL)
- Import `database/parking.sql` into MySQL
- Configure `.env` file for database connection

## 📡 API Endpoints
| Method | Endpoint              | Description              |
|--------|----------------------|--------------------------|
| POST   | `/api/auth/login`     | User Login              |
| POST   | `/api/auth/register`  | User Registration       |
| GET    | `/api/slots`          | Get Available Slots     |
| POST   | `/api/bookings`       | Book a Slot            |
| GET    | `/api/transactions`   | Get Transaction History |

## 🛠️ Future Enhancements
- **iOS Support** for the mobile app.
- **AI-based Parking Optimization**.
- **Integration with Smart Sensors** for real-time updates.

## 🤝 Contributors
- **Pranav Prashant Pawar** (Your Name)
- [GitHub](https://github.com/yourusername)

## 📜 License
This project is licensed under the MIT License.
