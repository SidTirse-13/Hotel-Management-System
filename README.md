# 🏨 Hotel Management System – Java

A console-based Hotel Management System built using Java and Object-Oriented Programming principles. This project simulates the operations of a hotel including room booking, food ordering, billing, and customer record management. It supports file handling for data persistence and multithreading for efficient background file saving.

---

## 📌 Features

- ✅ **Room Booking** – Supports single and double room booking with customer details.
- ✅ **Food Ordering** – Allows ordering food items to specific rooms with price calculation.
- ✅ **Billing System** – Generates bills based on room charges and food orders.
- ✅ **Unbooking Rooms** – Deallocates rooms and frees them for new customers.
- ✅ **Room Availability Check** – Displays available rooms with features.
- ✅ **Persistent Data Storage** – Uses file handling to save and load hotel data between sessions.
- ✅ **Multithreading** – Runs file writing in a background thread for smoother user experience.
- ✅ **Exception Handling** – Includes user-defined exceptions and handles runtime errors gracefully.
- ✅ **Menu-Driven Interface** – Interactive command-line menu system for user operations.

---

## 🧠 Concepts Used

- Object-Oriented Programming (OOP)
  - Classes & Objects
  - Inheritance
- File Handling
  - Serialization (`ObjectOutputStream`, `ObjectInputStream`)
- Multithreading
- Custom Exception Handling
- Java Collections (ArrayList)
- User Input (Scanner)

---

## 🛠️ Technologies

- Java
- Core Java Libraries (java.io, java.util, java.lang)
- Serialization
- Multithreading

---

## 🗂️ Project Structure

Hotel-Management-Project-Java/
├── Main.java
├── Hotel.java
├── Singleroom.java
├── Doubleroom.java
├── Food.java
├── NotAvailable.java
├── write.java
├── README.md
