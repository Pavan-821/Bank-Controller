# 🏦 ATM Simulation Software (Java)

A **console-based ATM simulation system** developed using **Core Java**.  
This project demonstrates fundamental Object-Oriented Programming concepts and basic in-memory data handling.

---

## 🎯 Project Overview

This application simulates common ATM functionalities in a single execution.  
Users can create accounts, log in securely using credentials, and perform basic banking operations through a menu-driven interface.

For the best experience, compile and run the program using the **Command Prompt / Terminal**.

---

## 🚀 Features

- Create a new bank account
  - Automatically generates a random **Account Number** and **PIN**
- Login using account number and PIN
- Perform ATM operations:
  - Balance inquiry
  - Deposit amount
  - Withdraw amount
  - Change PIN
  - Logout
- Displays **date and time stamps** on every successful login and logout
- Supports multiple user accounts in a single execution
- Terminates session on invalid input (fail-fast behavior)

---

## 🛠️ Technologies & Concepts Used

- **Programming Language:** Java
- **Execution Type:** Console-based application
- **Data Storage:** In-memory (ArrayList)

### Java Concepts Implemented

- Object-Oriented Programming (Classes & Objects)
- Encapsulation using private variables with getters and setters
- `ArrayList` for temporary data storage
- `Math.random()` for generating account numbers and PINs
- `Date` and `DateFormat` for timestamps
- `try-catch` blocks for exception handling

---

## ▶️ How to Run the Project

1. Clone or download the repository
2. Open **Command Prompt / Terminal**
3. Navigate to the project directory
4. Compile the program:
   ```
   javac ATM.java
   
## ⚠️ Limitations

- No persistent storage (all data is lost after the program exits)
- No encryption or hashing for user PINs
- No retry mechanism for invalid inputs
- Not suitable for real-world banking systems

---

## 📌 Purpose of the Project

This project is intended to:

- Practice **Core Java programming**
- Understand **Object-Oriented Programming (OOP) fundamentals**
- Gain experience with **console-based applications**
- Prepare for **academic evaluations and beginner-level interviews**

---

## 🔧 Possible Enhancements

- Implement file-based or database-backed storage
- Add PIN encryption or hashing for security
- Improve input validation and user retry handling
- Separate business logic from the user interface layer
