# 🏦 Bank Management System using Python (OOP)

## 📌 Project Overview
This project is a **console-based Bank Management System** developed using **Python and Object-Oriented Programming (OOP)** concepts.  
It simulates real-world banking operations such as account creation, deposits, withdrawals, fund transfers, and transaction tracking.

The project focuses on **clean architecture, abstraction, and scalability**, making it suitable for learning and demonstrating core software development skills.

---

## 📌 Problem Statement
Traditional banking systems involve multiple account types, transaction validation, and balance management.  
The goal of this project is to design a structured system that:
- Manages different account types
- Ensures secure transactions
- Maintains transaction history
- Applies OOP principles for code reusability and clarity

---

## 🛠️ Tools & Technologies Used
- Python
- Object-Oriented Programming (OOP)
- Abstract Base Classes (ABC)
- Exception Handling

---

## 🧱 System Design
The system is designed using the following classes:

### 🔹 Account (Abstract Class)
- Common attributes: account number, customer name, balance
- Common methods: deposit, get balance, transaction history
- Enforces implementation of withdrawal logic

### 🔹 SavingsAccount
- Inherits from Account
- Allows withdrawals only if sufficient balance is available

### 🔹 CurrentAccount
- Inherits from Account
- Supports overdraft limit functionality

### 🔹 Bank
- Manages multiple accounts
- Handles account creation
- Performs fund transfers between accounts

---

## ⚙️ Features Implemented
✔ Create savings and current accounts  
✔ Deposit money with validation  
✔ Withdraw money with balance checks  
✔ Overdraft facility for current accounts  
✔ Fund transfer between accounts  
✔ Account-wise transaction history  
✔ Error handling for invalid operations  

---

## 🔄 Project Workflow
1. User creates a bank account (Savings / Current)
2. Deposits initial or additional balance
3. Performs withdrawals or transfers
4. System validates rules and limits
5. All transactions are logged
6. User can view balance and transaction history

---

## ▶️ How to Run the Project
1. Clone the repository
```bash
git clone https://github.com/your-username/Bank-Management-System-Python.git
