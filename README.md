# Employee-Management-System
# Employee Management System

## Project Title

**Employee Management System** is a Java-based console application that demonstrates Object-Oriented Programming (OOP) concepts such as inheritance, polymorphism, encapsulation, records, and collections. The application allows users to manage employee information for different employee types, including Full-Time, Part-Time, and Contract employees.

---

## Features

* Add employee details.
* Support for three employee types:

  * Full-Time Employee
  * Part-Time Employee
  * Contract Employee
* Store employee address using Java Records.
* Store department information using Java Records.
* Display employee details.
* Demonstrates Java OOP concepts:

  * Inheritance
  * Polymorphism
  * Method Overriding
  * Encapsulation
  * Records
* Uses `ArrayList` to manage employee data.

---

## Project Structure

```
com.ems
├── model
│   ├── Employee.java
│   ├── FullTimeEmployee.java
│   ├── PartTimeEmployee.java
│   ├── ContractEmployee.java
│   ├── Address.java
│   └── Department.java
├── service
│   └── EmployeeService.java
└── main
    └── EmployeeManagementApp.java
```

---

## Installation

### Prerequisites

* Java JDK 17 or later
* Eclipse IDE / IntelliJ IDEA / VS Code

### Clone the Repository

```bash
git clone https://github.com/your-username/employee-management-system.git
```

### Navigate to the Project

```bash
cd employee-management-system
```

### Compile the Project

```bash
javac com/ems/model/*.java com/ems/service/*.java com/ems/main/*.java
```

---

## Usage

Run the application using:

```bash
java com.ems.main.EmployeeManagementApp
```

Example Output:

```
Employee ID : 101
Employee Name : John
Salary : 50000.0
Department : IT
Address : 12A, Anna Nagar, Salem
Bonus : 10000.0
```

---

## Technologies Used

* Java
* Java Records
* Object-Oriented Programming (OOP)
* Collections Framework (`ArrayList`)
* Eclipse IDE

---

## OOP Concepts Implemented

* Classes and Objects
* Inheritance
* Polymorphism
* Method Overriding
* Encapsulation
* Records
* Packages
* Collections

---

## Future Enhancements

* Update employee details.
* Delete employee records.
* Search employee by ID.
* File handling for data persistence.
* Database integration using MySQL.
* Graphical User Interface (GUI) using JavaFX or Swing.

---

## Author

**Fellah Hakeem**
