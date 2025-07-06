# 🛍️ ShopMate Redux – Shopping Cart App with React + Redux

![React](https://img.shields.io/badge/React-18-blue?logo=react)
![Redux](https://img.shields.io/badge/Redux-Toolkit-purple?logo=redux)
![Status](https://img.shields.io/badge/State%20Management-Redux%20Store-informational)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🚀 Project Overview

**ShopMate Redux** is a clean and modular **shopping cart** web app built with **React** and powered by **Redux Toolkit** for state management.  
This project demonstrates my transition from `useContext/useReducer` (used in [ShopKaro](../shopkaro)) to Redux, applying real-world architecture and scalable logic.

> 🔥 Built as part of my **learning-by-doing MERN journey**.

---

## 🎯 Key Learning Outcomes

| 🔧 Concept            | ✅ Applied In |
|----------------------|--------------|
| `Redux Toolkit`      | Global cart state, product list               |
| `createSlice()`      | Cart reducer with actions & reducers in one  |
| `configureStore()`   | Centralized Redux store                      |
| `useSelector` / `useDispatch` | Efficient state access + updates       |
| `React Router`       | Navigation between Home and Cart             |

---

## 🧠 Why Redux? (Compared to useContext/useReducer)

| Feature                | Context + useReducer ✅ | Redux Toolkit ✅✅ |
|------------------------|-------------------------|-------------------|
| Boilerplate            | Low                     | Moderate (but clean via Toolkit) |
| Scalable State Logic   | Medium                  | Excellent          |
| DevTools Integration   | ❌ None                 | ✅ Powerful Redux DevTools |
| Async Middleware       | ❌ Manual               | ✅ Built-in (`createAsyncThunk`) |
| Project Size Fit       | Small-Medium            | Medium-Large       |

---

## 📁 Folder Structure

```bash
shopmate-redux/
├── src/
│   ├── assets/            # Images & logos
│   ├── components/        # Navbar, ProductCard, CartItem
│   ├── hooks/             # Custom React hooks
│   ├── pages/             # Home, Cart views
│   ├── routes/            # Routing setup (React Router)
│   ├── store/             # Redux slices & store config
│   ├── App.jsx            # Root App
│   ├── index.jsx          # Entry point
│   └── index.css          # Styles
