# 📌 Blog / Web Application (Java MVC Based)

## 🚀 Project Overview

This project is a **full-stack web application** developed using **Java (Servlets & JSP), JDBC, and MySQL**, following an MVC-like architecture. It handles complete user interactions such as authentication, product management, cart operations, wishlist, reviews, appointments, and admin control.

The application demonstrates a real-world workflow where data flows from **frontend → controller → model → database → response**.

---

## 🧩 Key Features

### 🔐 User Authentication & Profile Management

- User Registration, Login, Logout
- Session-based authentication
- Profile update functionality
- Password handling and validation

---

### 🛍️ Product Management (Admin Side)

- Admin can **Add, Update, Delete, View products**
- Secured using admin session validation
- Product data stored in database

---

### 🛒 Cart Management

- Add to cart, remove, update quantity
- Cart mapped to logged-in user
- Session-based consistency

---

### ❤️ Wishlist Module

- Users can save products for later
- Prevents duplicate entries
- Linked with user account

---

### ⭐ Review & Rating System

- Users can give ratings and reviews
- Input validation to avoid invalid data
- Stored with product and user mapping

---

### 📅 Appointment Scheduling

- Users can book appointments
- Prevents duplicate bookings
- Validates existing records before insertion

---

### 🔍 Search Functionality

- Keyword-based product search
- Dynamic result display
- Efficient database querying

---

### 🧑‍💼 Admin Login & Dashboard

- Secure admin authentication
- Dashboard with system overview
- Manage users and products

---

## 🏗️ Tech Stack

Frontend:
- HTML
- CSS
- JSP

Backend:
- Java Servlets
- JDBC

Database:
- MySQL

Architecture:
- MVC (Model-View-Controller)

---

## 🔄 Application Flow

1. User interacts with frontend (forms/buttons)
2. HTTP request is sent to Controller (Servlet)
3. Controller processes request based on action
4. Model interacts with database using JDBC
5. Response is sent back to frontend (JSP)

---

## 📂 Project Structure

Controller/
   - Handles all HTTP requests and routing logic

Model/
   - Contains database operations (DAO classes)

View (JSP Pages)/
   - User interface and form handling

---

## 🔐 Security Features

- Session-based authentication
- Role-based access (User/Admin)
- Input validation to prevent errors

---

## 🎯 Key Highlights

- Real-world application flow
- Clean separation of concerns
- Multiple modules integrated in one system
- Scalable and maintainable structure

---

## 📌 Conclusion

This project demonstrates strong understanding of **full-stack development**, including **user management, database operations, session handling, and modular architecture**, making it suitable for real-world applications.
