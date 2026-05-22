# 🍽️ QuickBite – Interactive Restaurant Web App

QuickBite is a fully interactive restaurant web application built using **HTML, Tailwind CSS, and JavaScript**. It allows users to browse a menu, add items to a cart, log in, and track their order in real-time.

---

## 🚀 Features

### 🔐 Authentication

* Simple login system using **localStorage**
* User must log in before placing an order
* Displays username after login
* Logout functionality included

### 🏠 Home Page

* Attractive landing section with hero image
* Navigation bar with smooth page switching

### 🍴 Menu Page

* Dynamic menu rendering using JavaScript
* Food categories: Starters, Main Course, Desserts
* 🔍 Search functionality
* 🧩 Category filter
* Add to Cart feature

### 🛒 Cart System

* Add/remove items dynamically
* Increase/decrease quantity
* Auto-updating total price
* Cart stored in localStorage
* Empty cart UI

### 🚚 Delivery Tracking

* Step-by-step order tracking:

  * Confirmed → Cooking → On the Way → Delivered
* Animated progress bar
* Real-time status updates using `setInterval`

### 🎨 UI/UX

* Fully responsive design
* Built with **Tailwind CSS**
* Smooth animations and transitions
* Clean modern interface

---

## 🛠️ Technologies Used

* HTML5
* Tailwind CSS
* JavaScript (Vanilla JS)
* LocalStorage (for persistence)

---

## 📂 Project Structure

```
QuickBite/
│
├── index.html   # Main file (contains HTML, CSS, JS)
└── README.md    # Project documentation
```

---

## ▶️ How to Run

1. Download or clone the project
2. Open the folder
3. Double-click on `index.html`
4. The website will open in your browser

---

## 🔑 How It Works

* Menu data is stored in a JavaScript array
* Cart and user session are saved in **localStorage**
* Page navigation is handled without reloading (single-page behavior)
* Delivery tracking is simulated using timed updates

---

## ⚠️ Limitations

* No real backend (all data is stored locally)
* No real payment system
* Login is not secure (for demo purposes only)

---

## 🌟 Future Improvements

* Backend integration (Node.js / Firebase)
* Secure authentication (JWT)
* Online payments
* Order history page
* Admin dashboard
