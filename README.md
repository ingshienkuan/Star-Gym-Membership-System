# Star Gym Membership System

## Overview
The Star Gym Membership System is a **C++ fitness management software** designed to streamline operations for gym members and administrators. The system utilizes various **data structures** (linked lists, queues, hash tables) and sorting/search algorithms (bubble sort, linear search) to efficiently manage membership information, class bookings, equipment borrowing, payments, BMI tracking, and milestone updates.  

This project is developed as part of the TDS6213 Data Structures and Algorithms course at Multimedia University, Malaysia .

---

## Features
- **User Module**
  - Sign-up and login for members
  - Display member profile
  - Make payments
  - Borrow and return equipment
  - Book, join, and cancel fitness classes
  - Calculate BMI and track milestone progression

- **Admin Module**
  - Admin login
  - Search and sort member data by ID, height, weight, BMI, target BMI, or progression
  - Monitor class bookings and equipment usage

- **Additional Features**
  - Password validation and input error handling
  - Console color coding for visual feedback (BMI ranges)
  - User-friendly interactive menus

---

## Project Structure
```text
Star-Gym-Membership-System/
│
├─ src/                    # Source code files
│   ├─ main.cpp
│   ├─ login_signup.cpp
│   ├─ worker.cpp
│   ├─ fitnesscentre.cpp
│   ├─ class_booking.cpp
│   ├─ equipment_borrow.cpp
│   ├─ payment.cpp
│   ├─ milestone.cpp
│   └─ utils.cpp
│
├─ include/                # Header files
│   ├─ login_signup.h
│   ├─ worker.h
│   └─ fitnesscentre.h
│
├─ screenshots/            # Program screenshots
├─ README.md               # Project documentation
└─ report.pdf              # Final report
