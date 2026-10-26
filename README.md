# 🌍 Natours

## Advanced Node.js, Express & MongoDB Project

<p align="center">
  <b>Production-Level Backend Travel Booking API</b><br>
  Built with MVC Architecture, RESTful APIs, Authentication, Authorization, and Security Best Practices.
</p>

---
---

## 📖 About The Project

Natours is a backend API for a travel booking application where users can explore and book tours.

This project focuses on building a real-world backend system using Node.js, Express, MongoDB, and Mongoose. It follows MVC architecture and includes authentication, authorization, API security, error handling, and advanced query features.

---

## ✨ Features

### 🔐 Authentication & Authorization

- User signup and login
- JWT-based authentication
- Password encryption using bcrypt
- Role-based access control for Admin and User

### 🗺 Tour Management

- Create, read, update, and delete tours
- Advanced filtering and sorting
- Pagination
- Route aliasing
- MongoDB aggregation pipelines

### 🛡 Security

- Data sanitization
- NoSQL injection protection
- XSS protection
- HTTP security headers using Helmet
- Rate limiting

### ⚠ Error Handling

- Global error handling middleware
- Custom AppError class
- Operational and programming error handling
- Production-ready error responses

---

## 🛠 Tech Stack

| Category | Technologies |
|---|---|
| Backend | Node.js, Express.js |
| Database | MongoDB, Mongoose |
| Authentication | JWT, bcrypt |
| Security | Helmet, xss-clean, Rate Limiter |
| Tools | Postman, Nodemailer, Stripe |

---

## 📂 Project Structure

```bash
natours/
│
├── controllers/
├── models/
├── routes/
├── utils/
├── config.env
├── app.js
└── server.js
