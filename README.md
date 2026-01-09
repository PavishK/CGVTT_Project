# 🎓 Certificate Generating & Verification Website for Training & Internships

A **full-stack certificate management platform** built for **training institutes** to **manage courses, tasks, student submissions, and generate verifiable digital certificates**.

This system ensures **authenticity, transparency, and easy verification** of certificates using a **unique Certificate ID**.

🌐 **Live Project**: https://cgtt-client.onrender.com  
🔐 Protected with **Cloudflare Turnstile (Human Verification)**

---

## 🏆 Project Highlights

- 🔐 Secure authentication with Cloudflare verification  
- 📜 Auto-generated certificates after course completion  
- 🔎 Public certificate verification using Certificate ID  
- 🧑‍🎓 Student dashboard for courses, tasks & profile management  
- 🛠️ Admin dashboard for users, courses, enrollments & submissions  
- 📥 Download certificates as **PDF**  
- ⏱️ Task submission tracking with **timestamps**  
- 🔄 Redux-powered responsive sidebar navigation  

---

## 🧠 Tech Stack

### Frontend
- **React.js (Vite)**
- **Redux** (Sidebar & state management)
- **HTML2Canvas** (Certificate PDF generation)
- **Cloudflare Turnstile**
- **CSS / Responsive UI**

### Backend
- **Node.js**
- **Express.js**
- **JWT Authentication**
- **MySQL (TiDB Cloud)**
- **Nodemailer (Email support)**

### Deployment & Security
- **Render**
- **Cloudflare Tunnel**
- **Environment Variable Protection**

---

## 👨‍🎓 Student Features

### 🏠 Home Page
![Home](https://github.com/user-attachments/assets/cfae4d1d-3dbf-42f0-849a-78915eca027f)

### 📚 Courses Page
![Courses](https://github.com/user-attachments/assets/30447195-dfb3-41db-9f1e-9ad8f39a641f)

### 🧾 Certificate Verification (Using Certificate ID)
![Verifying](https://github.com/user-attachments/assets/5c8507ef-02e2-4914-a970-ba60379220ea)

![Certificate ID](https://github.com/user-attachments/assets/39f76cce-1485-4449-8ce1-23c08afce247)

### ℹ️ About Page
![About](https://github.com/user-attachments/assets/fd81002c-4c7b-4cc7-898d-f87b3c38fee4)

### 📤 Task Submissions with Status & Timestamp
![About](https://github.com/user-attachments/assets/7589f3ad-55fd-4785-8106-482d0cb888af)

### 👤 Profile Management
- Change full name  
- Update password  
- Delete account  

![Profile](https://github.com/user-attachments/assets/640ca6be-9563-4201-bd71-80c48ba33f6b)

---

## 🔐 Authentication (Cloudflare Protected)

### 🔑 Login
![Login](https://github.com/user-attachments/assets/13429a9a-01eb-4d56-8c9c-28b0880fc58d)

### 📝 Register
![Register](https://github.com/user-attachments/assets/f1c5953b-280b-449b-9313-7f53b175d68f)

---

## 📘 Course & Certificate Flow

### 📌 Course Tasks & Certificate Unlock
![Course Tasks](https://github.com/user-attachments/assets/386f4aca-31fd-44f3-9c69-fe5972982a7d)

### 📎 Task Submission (Google Drive PDF Link)
- Submit
- Unsubmit
- Track Status  

![Submit Task](https://github.com/user-attachments/assets/467d7fd8-b97f-4884-91d7-9f01557f5a8e)

### 📜 Certificate Download & Verification
![Verify Name](https://github.com/user-attachments/assets/a98ded69-eb84-489a-9a31-e9ade465781d)

![Download Certificate](https://github.com/user-attachments/assets/dc7993e7-7d04-4eed-8147-738871e364bd)

---

## 🛠️ Admin Features

### 📊 Admin Dashboard
![Dashboard](https://github.com/user-attachments/assets/5f281e3b-e9a8-4481-8566-1bd3fe25c82b)

### 👥 Manage Users
![Users](https://github.com/user-attachments/assets/277515dc-dd28-4272-8c45-8473594ea3ca)

### 🎓 Manage Enrollments
- Grant certificate access to students  

![Enrollments](https://github.com/user-attachments/assets/7b561a12-78ec-4dfb-91bd-7b3529deb13a)

### 📚 Manage Courses

![Courses Admin](https://github.com/user-attachments/assets/b3ce4527-20a8-46dd-8703-474fc4a2c4e7)

### 📥 Manage Submissions
![Submissions](https://github.com/user-attachments/assets/f6d0e33a-ac7c-4771-a625-48996f10460c)

---

## 📂 Project Structure

```

CGTT/
├── client-side/
│   ├── src/
│   ├── .env
│   └── package.json
│
├── server-side/
│   ├── routes/
│   ├── controllers/
│   ├── database/
│   ├── .env
│   └── server.js

````

---

## 🔐 Environment Variables

### 📁 Frontend (`client-side/.env`)
```env
VITE_SERVER_API="YOUR_BACKEND_URL"
VITE_SITE_KEY="YOUR_CLOUDFLARE_SITE_KEY"
VITE_SECRET_KEY="YOUR_SECRET_KEY"
````

### 📁 Backend (`server-side/.env`)

```env
HOST="YOUR_DB_HOST"
USER="YOUR_DB_USER"
PASSWORD="YOUR_DB_PASSWORD"
DATABASE="YOUR_DB_NAME"
DBPORT=4000
SSLSTATE=true

PORT=8080
JWT_SECRET="YOUR_JWT_SECRET"
COOKIE_SECRET="YOUR_COOKIE_SECRET"

CLOUDFLARE_SECRET_KEY="YOUR_CLOUDFLARE_SECRET"
CLIENT_URL="YOUR_FRONTEND_URL"

EMAIL_USER="YOUR_EMAIL"
EMAIL_PASS="YOUR_EMAIL_APP_PASSWORD"
```

> ⚠️ **Never push `.env` files to GitHub**

---

## 🚀 How to Run Locally

```bash
# Backend
cd server-side
npm install
npm run dev

# Frontend
cd client-side
npm install
npm run dev
```

---

## 📌 Key Concepts Used

* Certificate authenticity & verification
* Secure token-based authentication
* Role-based access (Admin / Student)
* Cloudflare bot protection
* PDF generation using HTML2Canvas
* Real-time task tracking with timestamps

---

## 🎯 Conclusion

This project provides a **complete digital solution for training institutes** to manage **courses, student performance, and certificate generation** with **public verification**.

It is **secure, scalable, and production-ready**, making it ideal for **real-world deployment**.

---

## 👨‍💻 Developed By

**Pavish K**
💻 MERN + MySQL Stack

⭐ *If you like this project, don’t forget to star the repository!* ⭐
Just tell me 👍

