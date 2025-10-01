# 🐾 PetHub – Online Pet Management System  

## 📌 Overview  
**PetHub** is a full-stack Java web-based application designed to help users **adopt, buy, and manage pets online**.  
The system provides a seamless platform for users to browse pets, make bookings, and for admins to manage users and listings efficiently.  

This project follows the **MVC** (Model-View-Controller) architecture and **DAO** (Data Access Object) pattern for clean, modular, and maintainable code.  

---

## 🎯 Features  
- 🔐 **User Authentication** – Secure login & registration for users and admins.  
- 🐕 **Pet Listings** – View, search, and filter available pets for adoption/purchase.  
- 📅 **Booking Management** – Book pets and manage adoption/purchase records.  
- 🛠️ **Admin Dashboard** – Admin can add, update, or delete pets and manage users.  
- 💾 **Database Integration** – Persistent storage of users, pets, and bookings using MySQL.  
- 🌐 **Responsive UI** – Clean and user-friendly interface using **HTML, CSS, and JavaScript**.  

---

## 🏗️ Tech Stack  
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Java, JSP, Servlets  
- **Database:** MySQL  
- **Design Patterns:** MVC, DAO  
- **Server:** Apache Tomcat  

---

## 📂 Project Structure  
PetHub/
│── src/
│ ├── model/ # Entity classes (User, Pet, Booking)
│ ├── dao/ # DAO interfaces & implementations
│ ├── controller/ # Servlets (Controllers)
│ └── util/ # DB connection utilities
│
│── WebContent/
│ ├── views/ # JSP pages (UI layer)
│ ├── css/ # Stylesheets
│ ├── js/ # JavaScript files
│ └── images/ # Project images
│
│── database/ # SQL scripts for schema & tables
│── README.md # Project Documentation
---

## ⚙️ Installation & Setup  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/PetHub.git
   cd PetHub
📚 Learnings

Implemented secure authentication with session management.

Performed CRUD operations using JDBC and DAO pattern.

Designed a responsive UI with HTML, CSS, and JavaScript.

Strengthened backend development using JSP & Servlets.

Applied MVC architecture for scalability and maintainability.

🚀 Future Enhancements

Integration with payment gateway for online purchases.

Add pet health records and medical history.

Enable email/SMS notifications for booking confirmations.

Deploy on cloud (AWS/Heroku) for real-time access.
