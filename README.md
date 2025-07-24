# 🚌 Bus Management System

A Java-based console application that simulates a comprehensive Bus Reservation System. It enables users to register, search and book buses, manage profiles, and earn loyalty points. Admins can manage users, bookings, and bus service data efficiently using text-based file handling.

---

## 📋 Table of Contents

- [Introduction](#introduction)
- [User Features](#user-features)
- [Admin Features](#admin-features)
- [Task Distribution](#task-distribution)
- [System Modules](#system-modules)
- [Features Summary](#features-summary)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [Conclusion](#conclusion)
- [Contributors](#contributors)

---

## 🔍 Introduction

The Bus Management System is designed to streamline operations in a bus transport service. It supports both **Users** and **Admins**, ensuring a seamless experience in handling bookings, seat selection, user data, and more.

---

## 👥 User Features

- **User Registration & Login** with validation  
- **Profile Management** (view/update personal details)  
- **Bus Search** by origin, destination, and travel date  
- **Seat Booking** with gender-based seat visualization  
- **Payment Options**: Debit Card, Mobile Banking, Loyalty Points, Cash, Credit Card  
- **Loyalty Points**: Earn and redeem on bookings  
- **E-Ticket Generation** after successful payment  

---

## 🔧 Admin Features

- **Admin Login** with authentication  
- **User Management** (add, update, delete, search)  
- **Bus Service Management** (routes, fares, buses)  
- **Booking Management** (view, edit, delete bookings)  
- **Direct File Handling** for users, buses, and bookings  

---

## 👩‍💻 Task Distribution

| Team Member         | Responsibilities |
|---------------------|------------------|
| **Areeba Tahir**    | User Module, File Handling, System Coordination |
| **Maryam Manahil**  | Booking Module, Payment Gateway, Ticket Generation |
| **Ayesha Altaf**    | Admin Module (Bus Management), Admin File Handling |
| **Muhammad Usman**  | UI/UX Console Design, Admin (User + Booking), Report Writing |

---

## 🧩 System Modules

### 1. User Module
- Registration, login, profile updates  
- Bus search  
- Seat selection and booking  
- Payment and loyalty points  
- Ticket generation  

### 2. Booking Module
- Seat availability and tracking  
- Booking ID generation  
- Booking file storage  
- Pre-booked seat simulation  

### 3. Admin Module
- Secure login  
- Managing users, buses, and bookings  
- File-level data updates  
- System data monitoring  

---

## 🌟 Features Summary

- Multi-class bus layout with gender-aware seating  
- Unique booking IDs with persistent storage  
- User-friendly ticket formatting  
- Modular codebase (User, Admin, Booking)  
- Realistic payment system with loyalty rewards  
- File-based data persistence for all entities  

---

## 💻 Technologies Used

- **Language**: Java  
- **Interface**: Console-based UI  
- **Data Storage**: Text files (`.txt`)  
- **No database**: Uses flat file handling for simplicity  

---

## 📁 Project Structure

bus-management-system/
├── src/ # Java source files
│ ├── Main.java
│ ├── UserModule.java
│ ├── AdminModule.java
│ └── BookingModule.java
├── data/ # Data files used by the system
│ ├── users.txt
│ ├── admins.txt
│ ├── booking.txt
│ └── bus_data.txt
├── README.md
└── .gitignore


---

## ▶️ How to Run

1. Open the project in any Java IDE (e.g., IntelliJ, Eclipse, NetBeans) or use terminal.  
2. Ensure the `data/` folder is in the root directory.  
3. Compile and run the `Main.java` file.

```bash
javac src/Main.java
java src/Main
