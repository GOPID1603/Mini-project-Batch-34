# Java Mini Projects - Batch 34

This repository contains two core Java console-based applications developed as part of a mini-project series. These projects demonstrate object-oriented programming, file handling, collections, streams, and exception handling in Java.

## Projects Included

### 1. ATM Simulation System
A classic console-based ATM interface that allows users to securely log in and manage their virtual bank accounts. 

**Key Features:**
- **User Authentication:** Validate login using Account Number and PIN.
- **Balance Inquiry:** Check current account balance.
- **Deposit & Withdrawal:** Add funds or withdraw money securely.
- **Transaction History:** View all past deposit and withdrawal activities.

**Files:** `ATM.java`, `Account.java`, `Transaction.java` (Package: `mini.project`)

### 2. Employee Management System
A comprehensive employee management utility that uses Java Collections and File I/O for persistent data storage.

**Key Features:**
- **CRUD Operations:** Add, view, update, and delete employees.
- **Search & Sort:** Search for employees by department or sort them ascending/descending by salary using Java Streams.
- **Persistent Storage:** Automatically saves and loads employee data to/from a local `employees.dat` file using Serialization.
- **Export Capabilities:** Export the employee database to a friendly CSV format.
- **Robust Error Handling:** Custom exceptions for duplicate accounts and invalid actions.

**Files:** `EmployeeManagementSystem.java` (Package: `mini.project2`)

---

## How to Run

### Prerequisites
Make sure you have Java Development Kit (JDK) installed on your system.
You can verify your installation by running `java -version` and `javac -version` in your terminal.

### Compiling and Running the ATM System
Open a terminal in the cloned repository folder and run the following commands:
```bash
javac -d . ATM.java Account.java Transaction.java
java mini.project.ATM
```
*(Default accounts are populated with AccNo: `1001` PIN: `1234` or AccNo: `1002` PIN: `4321`)*

### Compiling and Running the Employee Management System
```bash
javac -d . EmployeeManagementSystem.java
java mini.project2.EmployeeManagementSystem
```
