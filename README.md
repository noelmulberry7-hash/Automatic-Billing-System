# Automatic Billing System (Java + SQLite)

A desktop-based billing system developed using Java Swing and SQLite (JDBC).
The application allows users to add items, generate bills, and store billing records in a database for future reference.

---

## Features

- Add items with quantity
- Automatic price calculation
- Grand total generation
- Customer name support
- Save bills to SQLite database
- View previously saved bills
- Clean and structured GUI
- Real-time clock display

---

## Technologies Used

- Java (Core + OOP concepts)
- Java Swing (GUI)
- JDBC
- SQLite Database
- VS Code

---

## Project Structure

BillingSystem.java  
DBConnection.java  
billing.db (auto-created)  
sqlite-jdbc.jar  

---

## How to Run

1. Install Java (JDK 8 or above).
2. Add the SQLite JDBC `.jar` file to your project libraries.
3. Compile and run `BillingSystem.java`.
4. The database file (`billing.db`) will be created automatically on first run.

---

## Database Details

The system creates a table named `bills` with the following fields:

- id (Primary Key, Auto Increment)
- customer_name
- total_amount

---

## Academic Purpose

This project was developed as part of BCA coursework to demonstrate:

- GUI development using Swing  
- Database connectivity using JDBC  
- Event handling  
- Multithreading  
- Data persistence  

---

## Author

Noel Biju  
Anwin Gitto
