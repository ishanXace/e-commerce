# 🛒 DigiTech – Modern E-commerce Store

A responsive, modular e-commerce web app built with **React**. Users can browse, search, view product details in a modal, and manage a shopping cart with quantity control.

---

## 🚀 Features

### 🔍 Live Search
- Search for products by title in real time.

### 🏠 Homepage Sections
- Promo banners
- Trending products by category
- Recommended section
- Collection grid

### 🧾 Product Modal
- Quick view product details
- Add to cart functionality

### 🛒 Shopping Cart
- Quantity controls (+ / –)
- Auto-calculated subtotal, tax, delivery, discount, total
- Remove individual or all items

### 📱 Responsive Design
- Fully responsive layout using **CSS Modules**

---

## 🧩 Tech Stack

- **Frontend**: React, React Router DOM
- **Styling**: CSS Modules
- **State Management**: React Hooks (`useState`, `useEffect`)
- **Routing**: react-router-dom
- **Data**: Fetched from a dummy product API via `productService.js`

---

## 🗂️ Project Structure
src/
│
├── api/ # API fetch logic
│ └── productService.js
├── components/ # Reusable components
│ ├── NavBar.jsx
│ ├── BrandRow.jsx
│ └── ProductModal.jsx
├── pages/ # Route components
│ ├── HomePage.jsx
│ ├── CartPage.jsx
│ └── ShoppingSection.jsx
├── styles/ # CSS Modules
│ └── *.module.css
├── utils/
│ └── getProduct.js # Product filtering utility
├── App.jsx # Main app logic and routing
└── main.jsx # ReactDOM render

---

## 📦 Setup & Installation

### 1. Clone the Repository
```bash
git clone (https://github.com/ishanXace/e-commerce.git)
cd digitech-ecommerce
-> npm install
-> npm run dev
-> npm run build
