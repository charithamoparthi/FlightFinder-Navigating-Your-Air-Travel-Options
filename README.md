# ✈️ FlightFinder – Navigating Your Air Travel Options

## 🚀 Overview

**FlightFinder** is a full-stack flight booking web application designed to simplify and streamline the process of booking flight tickets.

Built using the MERN stack (MongoDB, Express, React, Node.js), it provides a secure and smooth experience from flight search to final booking confirmation.

---

## ✨ Features

* User Registration & Authentication (JWT-based)
* Real-time Flight Search & Filtering
* Class-wise Booking (Economy / Business)
* Interactive Seat Selection
* Secure Payment Integration (Razorpay / Stripe – Optional)
* Booking Confirmation & E-Ticket Generation
* Admin Dashboard for Flight Management
* Booking History Management

---

## 🛠 Tech Stack

### Frontend

* React.js
* Axios
* Bootstrap

### Backend

* Node.js
* Express.js

### Database

* MongoDB (Mongoose ODM)

### Authentication

* JWT (JSON Web Token)
* bcrypt for password hashing

### Payment Integration

* Razorpay / Stripe (Sandbox Mode Supported)

---

## 🏗️ Technical Architecture

```
Frontend (React.js)
    ↓ API Calls (Axios)
Backend (Node.js + Express)
    ↓
MongoDB Database
```

### Database Collections

* Users
* Flights
* Bookings

---

## 📂 Project Structure

### 🌐 Client (React)

```
client/
│
├── public/
│   └── index.html
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── App.js
│   └── index.js
│
└── package.json
```

### 🖥️ Server (Node + Express)

```
server/
│
├── controllers/
├── models/
├── routes/
├── middleware/
├── config/
├── server.js
└── package.json
```

---

## 🔄 Application Workflow

### 1️⃣ User Authentication

* Secure login & registration
* JWT-based session management

### 2️⃣ Flight Search

User provides:

* Departure
* Destination
* Travel Dates
* Passenger Count
* Travel Class

Backend returns filtered flight options.

### 3️⃣ Flight Selection

* View flight details
* Apply filters (Airline, Direct, Time)

### 4️⃣ Seat Selection

* Interactive seat map
* Class-based seat availability

### 5️⃣ Payment & Booking

* Secure payment gateway
* Booking stored in database
* Confirmation & E-ticket generated

### 6️⃣ Admin Panel

* Manage flights (CRUD)
* View bookings
* Manage users
* Dashboard analytics

---

## 🔐 Security Measures

* JWT Authentication
* Password hashing using bcrypt
* Input validation
* Role-based access (Admin/User)
* Secure payment integration

---

## 🧪 Testing

* API testing using Postman
* CRUD testing for flights
* Authentication validation
* Payment sandbox testing

---

## 🚀 Future Enhancements

* Email ticket confirmation
* QR code boarding pass
* Live flight status tracking
* PNR management
* Multi-language support

---

## 📦 Installation & Setup

### 1️⃣ Clone the Repository

```
git clone <your-repo-url>
cd FlightFinder
```

### 2️⃣ Setup Client

```
cd client
npm install
npm start
```

### 3️⃣ Setup Server

```
cd server
npm install
npm start
```

### 4️⃣ Environment Variables

Create a `.env` file in the server directory:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=6001
```

---



