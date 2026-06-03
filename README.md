# 🏨 Hotel Management Database System

A comprehensive Hotel Management Database developed using **Microsoft SQL Server** to streamline hotel operations, manage guest information, track reservations, monitor services, process payments and generate valuable business insights.

---

## 📌 Project Overview

This project simulates a real-world hotel management system by storing and managing data related to:

- 👤 Guests
- 🛏️ Rooms
- 🏢 Room Types
- 📅 Bookings
- 🧺 Hotel Services
- 📝 Service Usage
- 🧾 Invoices
- 💳 Payments

The database enables hotel management to efficiently manage daily operations and make informed business decisions through SQL reporting and analytics.

---

## 🎯 Project Objectives

✔️ Manage guest information

✔️ Track room availability and occupancy

✔️ Record and manage reservations

✔️ Monitor hotel services used by guests

✔️ Generate invoices and process payments

✔️ Produce business reports for management

✔️ Demonstrate advanced SQL concepts

---

## 🗂️ Database Structure

### 👤 Guests
Stores guest information including:
- Guest ID
- First Name
- Last Name
- Email Address
- Phone Number

---

### 🏢 Room Types
Defines the categories of rooms available in the hotel.

Examples:
- Single Room
- Double Room
- Deluxe Room
- Executive Room
- Family Room
- Presidential Suite

---

### 🛏️ Rooms
Stores information about individual hotel rooms.

Attributes:
- Room ID
- Room Number
- Room Type
- Floor Number
- Status

---

### 📅 Bookings
Records guest reservations and stay details.

Attributes:
- Booking ID
- Guest ID
- Room ID
- Check-In Date
- Check-Out Date
- Booking Date
- Booking Status

---

### 🧺 Services
Stores hotel services available to guests.

Examples:
- Laundry
- Spa Treatment
- Room Service
- Airport Pickup
- Gym Access
- Breakfast Service
- Dinner Service
- Swimming Pool Access
- Mini Bar
- Conference Room Booking

---

### 📝 Service Usage
Tracks services utilized by guests during their stay.

---

### 🧾 Invoices
Stores billing information generated from bookings and additional services.

---

### 💳 Payments
Stores payment records including:
- Payment Date
- Payment Method
- Amount Paid

---

## 🔗 Database Relationships

The following relationships were implemented using Primary Keys and Foreign Keys:

- 👤 One Guest ➜ Many Bookings
- 🏢 One Room Type ➜ Many Rooms
- 🛏️ One Room ➜ Many Bookings
- 📅 One Booking ➜ Many Service Usage Records
- 📅 One Booking ➜ One Invoice
- 🧾 One Invoice ➜ One Payment

---

## 🛠️ SQL Concepts Demonstrated

This project showcases the use of:

- ✅ CREATE DATABASE
- ✅ CREATE TABLE
- ✅ PRIMARY KEY
- ✅ FOREIGN KEY
- ✅ INSERT INTO
- ✅ SELECT Statements
- ✅ WHERE Clause
- ✅ ORDER BY
- ✅ GROUP BY
- ✅ HAVING
- ✅ INNER JOIN
- ✅ LEFT JOIN
- ✅ Aggregate Functions
  - COUNT()
  - SUM()
  - AVG()
  - MAX()
- ✅ CASE Statements
- ✅ DATEDIFF()
- ✅ Business Intelligence Queries

---

## 📊 Business Reports & Analytics

The database supports management reporting such as:

### 💰 Revenue Analysis
- Total Hotel Revenue
- Monthly Revenue Trends
- Revenue by Room Type
- Revenue by Payment Method

### 👥 Customer Analysis
- Highest Spending Guests
- Repeat Customers
- Guest Booking Patterns

### 🏨 Operations Analysis
- Occupancy Rate
- Room Availability
- Most Popular Room Type
- Average Length of Stay

### 🧺 Service Analysis
- Most Frequently Used Services
- Service Revenue Performance
- Guest Service Usage Trends

### 📈 Management Insights
- Cancellation Analysis
- Future Reservation Tracking

---

## 🚀 Technologies Used

- 💻 Microsoft SQL Server
- 🛠️ SQL Server Management Studio (SSMS)
- 🌐 GitHub

---

## 📷 Sample Features

✔️ Hotel Reservation Management

✔️ Guest Information Management

✔️ Service Tracking

✔️ Invoice Generation

✔️ Payment Processing

✔️ Revenue Reporting

✔️ Business Analytics

---

## 🎓 Academic Purpose

This project was developed as part of a Database Management Systems coursework project to demonstrate database design, implementation, normalization, SQL programming and business reporting techniques.

---

## 👩‍💻 Author

**Oluchi Okwu**

📚 Database Management Systems Project

🗓️ 2026

---

⭐ If you found this project useful, feel free to star the repository!
