# 🛒 ShopKaro – Shopping Cart using React + Context API + useReducer

![React](https://img.shields.io/badge/React-18.2-blue?logo=react)
![Context API](https://img.shields.io/badge/Context_API-State_Management-purple)
![Reducer](https://img.shields.io/badge/useReducer-Hooks-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-green)

---

## 📸 Preview

### 🏠 Home Page (with Cart Count)
![ShopKaro Home](./path-to/419a0edb-1227-483f-8727-94749159d56b.png)

### 🛒 Cart Page (with Item Summary)
![ShopKaro Cart](./path-to/5607206b-ba29-47bc-b345-b9affa602a7c.png)

> 📝 Update image paths above after hosting or adjust if putting this in your local project.

---

## 🚀 Project Purpose

**ShopKaro** is a mini e-commerce cart project built as a **learning demo** to understand:
- 🧠 `useContext` for global state
- 🌀 `useReducer` for predictable state updates
- 🛍️ Cart add/remove functionality
- 🔄 Component re-rendering based on state changes

---

## 📁 Project Structure

```
shopkaro/
├── public/ # Static assets
├── src/
│ ├── components/ # Navbar, Cart, Home, ProductCard
│ ├── context/ # Context & reducer logic
│ ├── data.js # Product data
│ ├── App.js # App setup with routing
│ └── index.js # React root
├── package.json
└── README.md
```


## 🧠 Concepts Covered

| Feature                          | Description |
|----------------------------------|-------------|
| ✅ `useContext`                  | Global state sharing across components |
| ✅ `useReducer`                  | Centralized cart logic (add/remove) |
| 🧩 Component composition         | Breaking UI into reusable pieces |
| 🧪 Derived state (`Cart Count`) | Auto updates on state changes |
| ⚛️ React Router (if used)       | Page navigation |

---

## 🛠 Technologies Used

- React 18+
- useContext + useReducer
- Basic CSS / Styled Components / Tailwind (based on your setup)
- React Router DOM (if present)

---

## 💻 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/8057vivek/mern-projects.git
cd shopkaro
```

### 2. Install Dependencies  
```bash
npm install
```

### 3. Run The App  
```bash
npm start

```
The app will run at: [http://localhost:3000](http://localhost:3000)
