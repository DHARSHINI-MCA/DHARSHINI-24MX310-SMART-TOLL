# DHARSHINI-24MX310-SMART-TOLL
# 🚀 SMART TOLL

### Assisted Intelligent Toll Cost Estimation, Route Optimization & Pre-Trip Alert System

---

## 📌 Overview

SMART TOLL is a web-based system designed to enhance highway travel by providing **accurate toll cost estimation**, **route optimization**, and **real-time alerts**.
It helps users plan trips efficiently by analyzing multiple routes, estimating expenses, and ensuring sufficient FASTag balance before travel.

---

## 🎯 Key Features

### 🔔 Pre-Alert Notification System

Provides alerts before approaching toll plazas to avoid last-minute delays and ensure smooth travel.

### 💰 Toll Cost Estimation

Calculates total toll expenses in advance based on vehicle type and selected route.

### 🛣️ Route Optimization & Comparison

Fetches multiple routes and compares them based on **distance, time, and toll cost** to suggest the best option.

### 🚗 Vehicle Management

Allows users to register and manage multiple vehicles with FASTag details and balances.

### 💳 FASTag Balance Verification

Checks whether the user has sufficient balance before starting the trip and alerts if insufficient.

### 📍 Real-Time Location Tracking

Tracks user location and detects nearby toll plazas dynamically during travel.

---

## ⚙️ Technologies Used

### 🖥️ Frontend

* HTML
* CSS
* JavaScript

### 🔧 Backend

* Node.js
* Express.js

### 🗄️ Database

* MongoDB (with Geospatial Queries)

### 🌐 APIs

* Google Maps Directions API
* Razorpay Payment Gateway

---

## 🧠 Algorithms & Concepts Used

* **Haversine Formula** → Used to calculate distance between route points and toll plazas
* **Polyline Decoding Algorithm** → Converts encoded route paths into GPS coordinates
* **Geospatial Query ($near)** → Detects toll plazas within a specific radius
* **Route Comparison Logic** → Selects optimal route based on cost/time/distance
* **Pricing Rules Logic** → Applies NHAI toll rules and vehicle-based pricing

---

## 🏗️ System Architecture

1. User enters source and destination
2. System fetches multiple routes from Google Maps API
3. Polylines are decoded into coordinates
4. Toll plazas are detected using geospatial queries
5. Toll cost is calculated based on vehicle type
6. Routes are compared and optimized
7. Alerts are provided before toll arrival

---

## 📂 Project Structure

```
SMART-TOLL/
│
├── backend1/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── app.js
│   ├── package.json
│   └── .env
│
├── frontend/
│   ├── js/
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── route.html
│   ├── recharge.html
│   └── addVehicle.html
```

---

## ▶️ How to Run the Project

### 🔹 Step 1: Clone the Repository

```
git clone <your-repo-link>
cd SMART-TOLL/backend1
```

---

### 🔹 Step 2: Install Dependencies

```
npm install
```

---

### 🔹 Step 3: Setup Environment Variables

Create a `.env` file inside `backend1`:

```
PORT=5001
JWT_SECRET=mysupersecretkey
MONGO_URI=your_mongodb_connection_string
GOOGLE_MAPS_API_KEY=your_api_key
RAZORPAY_KEY_ID=your_key
RAZORPAY_KEY_SECRET=your_secret
SMARTTOLL_EMAIL=smarttoll.demo2026@gmail.com
SMARTTOLL_EMAIL_PASSWORD=APP PASSWORD
```

---

### 🔹 Step 4: Run the Server

```
node app.js
```

Server will run on:
👉 http://localhost:5001

---

---

## 💡 Future Enhancements

* 📱 Mobile application (Android/iOS)
* 🤖 AI-based route prediction
* 📊 Analytics dashboard for travel insights

---

## 🚧 Limitations

* Depends on external APIs (Google Maps)
* Requires internet connectivity
* Static toll dataset (can be improved with real-time data)

---

## 📊 Impact of the Project

* Reduces travel uncertainty
* Helps users save time and cost
* Improves toll management efficiency
* Enhances digital highway experience

---

## 👩‍💻 Author

**Dharshini V - 24MX310**
MCA – PSG College of Technology

---

## 🙌 Acknowledgement

I would like to thank my project guide and institution for their guidance and support in completing this project successfully.

---

## 📜 License

This project is developed for academic purposes.
