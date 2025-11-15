# Nestly  
Full-stack room booking application built with React & Spring Boot

📦 **Nestly – Full Stack Room Rental Application**

Nestly is a full-stack web application that allows users to browse, filter, and book rental rooms easily.  
This repository acts as the **main parent repository**, linking both the frontend and backend projects.

---

## 📁 Repository Structure

```
Nestly/
├── nestly-frontend/   → React + Vite application  
└── nestly-backend/    → Spring Boot REST API
```

✔️ Frontend & backend are kept as **separate repositories**, and referenced inside this main project.  
You may add them as **Git submodules**, or simply clone both repos manually.

---

## 🔗 Project Repositories

### **Frontend**
- **Tech:** React + Vite  
- **Repo:** `nestly-frontend/`  

### **Backend**
- **Tech:** Spring Boot (Java)  
- **Repo:** `nestly-backend/`  

---

## ✨ Features

### **Frontend**
- User signup & login  
- Room listings & filtering  
- Room details page  
- Full booking flow  
- Responsive UI with animations  

### **Backend**
- REST APIs for rooms & bookings  
- Secure authentication (JWT)  
- Database integration  
- Room filtering & search APIs  

---

## ⚙️ Tech Stack

### **Frontend**
- React.js  
- Vite  
- React Router  
- Axios  
- Framer Motion  

### **Backend**
- Spring Boot  
- Java  
- Spring Security  
- Spring Data JPA  
- MySQL / PostgreSQL  

---

## 🛠️ Environment Variables

### **Frontend (`.env`)**
```env
VITE_API_BASE_URL=
```

### **Backend (`.env` or `application.properties`)**
```env
DB_URL=
DB_USERNAME=
DB_PASSWORD=
JWT_SECRET=
```

---

## 🚀 Run Locally

### 1️⃣ Clone the main repository
```sh
git clone https://github.com/DodlaSrichaithanya123/Nestly.git
cd Nestly
```

### 2️⃣ Clone the frontend & backend inside this folder
```sh
git clone https://github.com/DodlaSrichaithanya123/nestly-frontend.git
git clone https://github.com/DodlaSrichaithanya123/nestly-backend.git
```

---

## ▶️ Start Frontend
```sh
cd nestly-frontend
npm install
npm run dev
```

---

## ▶️ Start Backend
```sh
cd nestly-backend
mvn spring-boot:run
```

---

## 📌 Notes
- This repository only serves as a **main project overview**.  
- Full source code is inside the respective frontend & backend repositories.  

---
