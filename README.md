# Nestly
Full-stack room booking application built with React &amp; Spring Boot

📦 Nestly – Full Stack Room Rental Application

Nestly is a full-stack web application that helps users browse, filter, and book rental rooms with ease.
This repository acts as the main parent repository, containing both the frontend and backend code references.

📁 Repository Structure
Nestly/
├── nestly-frontend/   → React + Vite application
└── nestly-backend/    → Spring Boot REST API


✅ Frontend & backend are kept as separate repositories, but referenced inside this main project.
You may add them as Git submodules or simply clone both repos manually.

🔗 Project Repositories
Frontend

Technology: React + Vite
Directory: nestly-frontend/

Backend

Technology: Spring Boot (Java)
Directory: nestly-backend/

✨ Features

Frontend

User signup/login
Room listings
Room details
Booking UI flow
Responsive UI with animations

Backend

REST APIs for rooms & bookings
Secure authentication
Database integration
Room filtering/search API

⚙️ Tech Stack
Frontend

React.js
Vite
React Router
Axios
Framer Motion

Backend

Spring Boot
Java
Spring Security
Spring Data JPA
MySQL/PostgreSQL

🛠️ Environment Variables
Frontend (.env)
VITE_API_BASE_URL=

Backend (.env or application.properties`)
DB_URL=
DB_USERNAME=
DB_PASSWORD=
JWT_SECRET=

🚀 Run Locally
1️⃣ Clone the main repository
git clone https://github.com/DodlaSrichaithanya123/Nestly.git
cd Nestly

2️⃣ Clone the frontend & backend into this folder
git clone https://github.com/DodlaSrichaithanya123/nestly-frontend.git
git clone https://github.com/DodlaSrichaithanya123/nestly-backend.git

▶️ Start Frontend
cd nestly-frontend
npm install
npm run dev

▶️ Start Backend
cd nestly-backend
mvn spring-boot:run
