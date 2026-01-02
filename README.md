# Backend-Systems-Development

This repository contains a collection of backend-focused applications developed during my Software Engineering Internship. These projects demonstrate the application of Object-Oriented Programming (OOP) principles, relational database management, and robust error handling in Java.


## 🏦 1. FinTrack: Secure Banking Engine
*A robust banking simulator built to handle core financial operations with data persistence.*

* **Core Functionality:** User account lifecycle management, secure deposit/withdrawal processing, and real-time ledger balance updates.
* **Logic Focus:** Transaction atomicity (ensuring balance integrity) and strict input validation to prevent overdrafts.
* **Technologies:**  **Language:** Java (JDK 11+)
    * **Database:** MySQL (Relational storage for accounts and transaction logs)
    * **Connectivity:** JDBC (Java Database Connectivity)

## 📚 2. LibraFlow: Institutional Resource Manager
*An automated Library Management System (LMS) designed to optimize administrative workflows.*

* **Core Functionality:** Dynamic book cataloging, member registration, and automated check-in/check-out tracking.
* **Logic Focus:** Managing complex relational data (mapping books to specific users) and implementing automated availability status toggling.
* **Technologies:**  **Language:** Java
    * **Database:** MySQL (Normalized tables for Books, Members, and Transactions)
    * **Architecture:** Modular Class Design (DAO Pattern)

---

## 🛠️ Key Technical Competencies
* **RDBMS Management:** Designing and querying MySQL databases to maintain data integrity across multiple tables.
* **CRUD Operations:** Implementing Create, Read, Update, and Delete logic via JDBC.
* **OOP Principles:** Utilizing Inheritance, Encapsulation, and Polymorphism to create reusable and maintainable code.
* **Exception Handling:** Building custom try-catch blocks to handle SQL exceptions and invalid user inputs gracefully.

---

## 📂 Project Structure
```text
├── Banking System/           # Java Source Files (.java) & SQL Schemas
├── Library Management/       # Java Source Files (.java) & SQL Schemas
└── README.md                 # Project documentation
