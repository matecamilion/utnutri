# 🥗 UTNutri - Nutrition Patient Management App

## 👨‍💻 About This Project

UTNutri is a team project developed as part of my training as a software developer.

I contributed to the frontend development using Angular, focusing on application structure, routing, authentication flow, and user experience.

This project represents my ability to build a modular and scalable frontend application simulating real-world scenarios.

---

## 📋 What is UTNutri?

UTNutri is a modern frontend application built with Angular that allows nutritionists to manage patients, consultations, schedules, and nutritional plans efficiently.

The project uses JSON Server as a mock backend to simulate a real-world full-stack application.

---

## 🚀 Features

### Patient Management
- Create, edit, and delete patients  
- Real-time search by name, email, or phone  
- Detailed patient profile  
- Responsive and adaptive listing  

### Consultation History
- Record patient metrics (weight, height, body fat, muscle mass)  
- Track patient progress over time  
- Responsive table and mobile-friendly view  

### Nutrition Plan
- Create and edit personalized meal plans  
- Organized by meals (breakfast, lunch, snack, dinner)  
- Notes and snack sections  

### Appointment System
- Schedule appointments with date and time  
- Edit and reschedule appointments  
- Automatic time validation (7:00 - 19:00)  
- Status management (Pending, Completed, Cancelled)  

### Authentication
- Login system  
- Route protection using guards  
- Automatic redirection for unauthorized users  

---

## 🛠 Tech Stack

- Angular  
- TypeScript  
- RxJS  
- Angular Signals  
- JSON Server  
- HTML / CSS  

---

## ⚠️ Backend Note

- No real backend implemented  
- JSON Server is used to simulate REST API  
- Data is stored locally in `database/db.json`  

---

## 📱 Responsive Design

- Desktop: Full table view  
- Tablet: Scrollable layout  
- Mobile: Card-based layout  

---

## 📂 Project Structure
src/
├── app/
│ ├── auth/
│ ├── paciente/
│ ├── consultas/
│ ├── plan-nutricional/
│ ├── turnos/
│ └── app.routes.ts
├── styles.css
└── index.html

database/
└── db.json

## ▶️ Getting Started

### Requirements
- Node.js (v18+)
- npm or yarn

#Author
Mateo Camilion and Santiago Poidomani
Junior Software Developer
