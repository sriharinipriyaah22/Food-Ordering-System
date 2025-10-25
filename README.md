# 🍔 Food-Ordering-Systems

The **Food-Ordering-Systems** is a web-based application designed to make online food ordering simple and efficient. Users can browse a variety of food items, add them to the cart, apply coupons or combo offers, and place orders with ease. Admins can manage food items, categories, orders, and customer data from a dedicated dashboard.

---

## 🚀 Features

- 🛒 **Browse and search food items by category**  
- 📦 **Add to cart and place online orders**  
- 👤 **User registration and login**  
- 📊 **Admin panel for managing products and orders**  
- 📍 **Delivery address input and order tracking**  
- 💳 **Payment method integration (optional)**  
- 📱 **Responsive UI for mobile and desktop**  

---

## 🛠️ Tech Stack

- **Frontend:** React.js + Vite / HTML / CSS / JavaScript  
- **Backend:** Node.js + Express  
- **Database:** MongoDB  
- **Authentication:** JWT  

---

## 📁 Project Structure

/client → Frontend code (React + Vite)
/server → Backend API and logic (Node.js + Express)
/config → Configuration files (DB, auth, etc.)

2️⃣ Install dependencies
    Frontend

    cd frontend
    npm run dev


    Backend

    cd backend
    npm run server

3️⃣ Configure environment variables
    Create a .env file in /server:
       PORT=5000
       MONGO_URI=your_mongodb_connection_string
       JWT_SECRET=your_secret_key
