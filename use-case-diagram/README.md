# 🧩 Use Case Diagram – Airbnb Clone Backend

## 🎯 Objective

This document visualizes the key interactions between users and the **Airbnb Clone backend system**, highlighting how different actors engage with major functionalities such as **user registration**, **property management**, **bookings**, and **payments**.

---

## 👥 Actors

- **Guest** – Registers, searches for properties, books stays, makes payments, and leaves reviews.
- **Host** – Lists, edits, or removes properties, views bookings, and receives payments.
- **Admin** – Monitors users, listings, bookings, and payments.
- **Payment Gateway** – Handles secure transactions between guests and hosts.
- **Notification Service** – Sends email or in-app alerts for key events like bookings and payments.

---

## ⚙️ System Overview

The **Airbnb Clone Backend** provides core functionalities including:

- Secure authentication using JWT
- Role-based access control (Guest, Host, Admin)
- Property listing management
- Booking and payment handling
- Notifications and reviews management

---

## 📊 Use Case Coverage

| Actor                    | Core Interactions                                                            |
| ------------------------ | ---------------------------------------------------------------------------- |
| **Guest**                | Register/Login, Search Properties, Book Property, Make Payment, Leave Review |
| **Host**                 | Manage Listings, View Bookings, Respond to Reviews, Receive Payments         |
| **Admin**                | Manage Users, Monitor Listings, Review Payments                              |
| **Payment Gateway**      | Process Payments, Send Confirmation                                          |
| **Notification Service** | Send Booking/Payment Alerts                                                  |

---

## 🖼️ Use Case Diagram

Below is the visual representation of system interactions between users and the backend:

> `![Use Case Diagram](./usecase.png)`

---

## 🗂️ Directory Structure

alx-airbnb-project-documentation/
└── use-case-diagram/
├── use-case-diagram.png # Exported Draw.io diagram
└── README.md # This documentation file

---

## 🧾 Author

**Naana Shifah**  
ALX Software Engineering Program  
Project: _Airbnb Clone Backend – Documentation Phase_
