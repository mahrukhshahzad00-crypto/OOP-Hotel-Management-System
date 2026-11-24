# Hotel Management System

A Java-based Hotel Management System developed as an Object-Oriented Programming (OOP) academic project. The system organizes hotel operations through dedicated components for managing employees, guests, rooms, and reservations.

## Project Overview

The project demonstrates the practical application of object-oriented programming principles in a hotel management environment. It uses a modular structure with separate entity and controller classes to organize hotel operations.

## Key Features

- Employee management
- Guest management
- Room management
- Reservation management
- Console-based application
- Modular code structure
- Object-oriented design

## Technologies Used

- Java
- Java Development Kit (JDK 21)
- Object-Oriented Programming (OOP)
- Java Module System
- Visual Studio Code

## OOP Concepts

- Classes and Objects
- Encapsulation
- Abstraction
- Modular Programming
- Separation of Responsibilities

## Project Structure

```text
OOP-Hotel-Management-System/
│
├── src/
│   ├── HotelManagementSystem/
│   │   ├── Employee.java
│   │   ├── EmployeesController.java
│   │   ├── Guest.java
│   │   ├── GuestsController.java
│   │   ├── Main.java
│   │   ├── Reservation.java
│   │   ├── ReservationsController.java
│   │   ├── Room.java
│   │   └── RoomsController.java
│   └── module-info.java
│
├── .gitignore
└── README.md
```

## How to Run

### Prerequisites

- Java JDK 21
- VS Code or any Java-compatible IDE

### Compile the Project

Open the terminal in the project root directory and execute:

```powershell
javac -d bin .\src\module-info.java .\src\HotelManagementSystem\*.java
```

### Run the Application

```powershell
java --module-path bin -m HotelManagementSystem/HotelManagementSystem.Main
```

## Learning Outcomes

- Understanding object-oriented software design
- Implementing Java classes and objects
- Organizing application logic using controllers
- Managing relationships between system entities
- Developing modular Java applications

## Future Improvements

- Graphical user interface
- Database integration using MySQL
- User authentication and authorization
- Automated billing and invoicing
- Advanced room availability tracking
- Persistent data storage

## Academic Information

- **Course:** Object-Oriented Programming
- **Degree:** Computer Engineering
- **University:** COMSATS University Islamabad, Lahore Campus
- **Semester:** 5th

## Author

**Mahrukh Shahzad**

Computer Engineering Student

## Acknowledgments

Original source code attributions are retained where applicable.

---

This repository is intended for educational and academic purposes.
