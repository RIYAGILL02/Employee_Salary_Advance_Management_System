# 💼 Employee Salary Advance Management System (Java)

A console-based **Employee Salary Advance Management System** developed in **Java**, focusing on clean
Object-Oriented Programming (OOP) design.  
The project simulates how organizations manage employee records and salary-related operations in a
structured and extensible way.

---

## 📌 Project Overview

This application demonstrates a real-world payroll-style system where employees can be added,
managed, and displayed efficiently.  
It is intentionally kept lightweight and readable, making it ideal for **students, beginners, and
placement preparation**.

---

## ✨ Key Features

- Abstract `Employee` class as a blueprint  
- Supports multiple employee types  
- Automatic unique Employee ID generation  
- Salary calculation using **polymorphism**  
- Add, remove, and list employees  
- Simple console-based interaction  

---

## 🛠️ Technologies Used

- **Programming Language:** Java  
- **Concepts Applied:**  
  - Abstraction  
  - Inheritance  
  - Polymorphism  
  - Encapsulation  
  - Collections (`ArrayList`)  

---

## 📂 Project Structure

Employee-Salary-Advance-Management
│
├── src
│ ├── Employee.java
│ ├── EmployeeUse.java
│
└── README.md


---

## ⚙️ How the System Works

1. `Employee` is an abstract class containing common employee details.
2. Different employee types implement their own salary logic.
3. Employees are stored dynamically using an `ArrayList`.
4. The system allows:
   - Adding new employees
   - Removing employees using Employee ID
   - Displaying all employee records

---

## ▶️ How to Run the Project

### Option 1: Using Command Line
```bash
javac EmployeeUse.java
java EmployeeUse

Initial Employee List:
Employee ID: 1 | Name: Rahul | Salary: 45000
Employee ID: 2 | Name: Sneha | Salary: 32000

--------------------------------

Employee with ID 3 removed successfully.

Remaining Employees:
Employee ID: 1 | Name: Rahul | Salary: 45000
Employee ID: 2 | Name: Sneha | Salary: 32000
