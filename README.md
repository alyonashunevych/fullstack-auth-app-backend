# Auth App Backend

Backend API for handling authentication, authorization, and user management.

## 🔗 Live API

https://fullstack-auth-app-backend.onrender.com

⚠️ Note: The server may take up to 30 seconds to start (free hosting)

---

## 🔗 Frontend Repository

https://github.com/alyonashunevych/fullstack-auth-app

---

## 🛠️ Tech Stack

* Node.js
* Express
* PostgreSQL
* Prisma
* JWT (access & refresh tokens)

---

## ✨ Features

* User authentication & authorization  
* Email-based account activation  
* JWT access & refresh token flow  
* Protected routes  
* Password reset functionality  
* Profile management  

---

## 📡 API

### Auth

* `POST /auth/registration` — register a new user  
* `GET /auth/activation/:email/:token` — activate account via email link  
* `POST /auth/login` — login user  
* `GET /auth/refresh` — refresh access token (uses cookies)  
* `POST /auth/logout` — logout user  

---

### Password

* `POST /auth/request-password-reset` — request password reset email  
* `POST /auth/reset-password` — set new password  
* `GET /auth/reset-password/validate/:token` — validate reset token  

---

### User

* `POST /users/check` — verify user password  
* `PATCH /users` — update user data (name, email, password)  

---

## 🚀 Run locally

```bash
git clone https://github.com/alyonashunevych/fullstack-auth-app-backend.git
cd fullstack-auth-app-backend
npm install
npm start
```

## 👤 Author

https://github.com/alyonashunevych
