# 🔄 Data Flow Diagram (DFD) – Airbnb Clone Backend

## 🎯 Objective

This document presents the **Data Flow Diagram (DFD)** for the Airbnb Clone backend system.  
It visualizes how data moves through the system — from user inputs to backend processes and database storage — across key modules like **User Management**, **Property Listings**, **Bookings**, and **Payments**.

---

## 🧩 Key Entities

| Entity       | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| **User**     | Represents both Guests and Hosts interacting with the platform.                   |
| **Property** | Represents listings created by hosts, including location, price, and amenities.   |
| **Booking**  | Represents reservation data between guests and hosts.                             |
| **Payment**  | Represents financial transactions between guests, hosts, and the payment gateway. |
| **Admin**    | Oversees users, properties, bookings, and payments.                               |

---

## ⚙️ Core Processes

1. **User Registration & Authentication**

   - Input: User details (email, password, role)
   - Process: Validate credentials, hash passwords, issue JWT token
   - Output: Authenticated user session

2. **Property Management**

   - Input: Host adds or updates property details
   - Process: Store property data in database, link to host ID
   - Output: Updated property listings

3. **Booking System**

   - Input: Guest selects property and booking dates
   - Process: Validate availability, create booking record
   - Output: Booking confirmation and notification

4. **Payment Processing**

   - Input: Guest payment information
   - Process: Send transaction request to payment gateway
   - Output: Payment confirmation, update booking status

5. **Review and Notification Flow**
   - Input: User actions (booking, payment, review)
   - Process: Trigger event-based notifications
   - Output: Emails, in-app messages, or admin alerts

---

## 🧠 Data Stores

| Data Store           | Description                                     |
| -------------------- | ----------------------------------------------- |
| **Users DB**         | Stores user profiles, credentials, and roles.   |
| **Properties DB**    | Contains all listing details.                   |
| **Bookings DB**      | Stores all booking transactions and statuses.   |
| **Payments DB**      | Records all completed and pending payment data. |
| **Notifications DB** | Keeps logs of system notifications.             |

---

## 📊 Data Flow Description

- **Users** interact with the system through the API.
- The **API Server** processes requests and interacts with **Data Stores**.
- The **Payment Gateway** securely handles transaction data and sends responses to the backend.
- The **Notification Service** delivers system messages based on backend triggers.

---

## 🖼️ Data Flow Diagram

> 🧠 **Placeholder:** Insert your exported PNG here after creating it in Draw.io.  
> Example:  
> `![Data Flow Diagram](./data-flow.png)`

---

## 🗂️ Directory Structure

alx-airbnb-project-documentation/
└── data-flow-diagram/
├── data-flow.png # Exported diagram from Draw.io
└── README.md # This documentation file

---

## 🧾 Author

**Naana Shifah**  
ALX Software Engineering Program  
Project: _Airbnb Clone Backend – Documentation Phase_
