# Employee Management System

A Java-based Employee Management System developed using **Hibernate ORM, MySQL, and Maven**. This project demonstrates how to connect a Java application with a MySQL database using Hibernate and perform employee management operations.

## 🚀 Features

* Add employee records
* Retrieve employee records
* Update employee records
* Delete employee records
* MySQL database integration
* Hibernate ORM for database operations
* Maven dependency management

## 🛠️ Technologies Used

* **Java**
* **Hibernate ORM**
* **MySQL**
* **Maven**
* **XML**
* **Eclipse IDE**

## 📂 Project Structure

```text
employee-management-system/
│
└── employee-management-system/
    │
    ├── src/
    │   └── main/
    │       │
    │       ├── java/
    │       │   └── com/
    │       │       └── employee/
    │       │           └── employee_management_system/
    │       │               ├── App.java
    │       │               └── Employee.java
    │       │
    │       └── resources/
    │           └── hibernate.cfg.xml
    │
    ├── pom.xml
    └── README.md
```

### `App.java`

The main application class responsible for executing the Employee Management System and performing database operations using Hibernate.

### `Employee.java`

The employee entity class that represents employee data and defines the Hibernate mapping between the Java object and the database table.

### `hibernate.cfg.xml`

The Hibernate configuration file used to configure the database connection and Hibernate properties.

### `pom.xml`

The Maven configuration file used to manage project dependencies and build configuration.

## 🗄️ Database

This project uses **MySQL** as the database and **Hibernate ORM** to communicate with the database.

The employee data is stored in a database table mapped to the `Employee` entity.

## ⚙️ Prerequisites

Before running the project, install:

* Java JDK
* Maven
* MySQL Server
* Eclipse IDE

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/shaikkhaja47/employee-management-system.git
```

### 2. Open the Project

Import the project into Eclipse as an existing **Maven Project**.

### 3. Configure MySQL

Create the required MySQL database.

Then configure your database connection in:

```text
src/main/resources/hibernate.cfg.xml
```

Set your:

* Database URL
* MySQL username
* MySQL password

**Do not commit your actual database password to GitHub.**

### 4. Update Maven Dependencies

In Eclipse:

```text
Right Click Project
→ Maven
→ Update Project
```

Maven will download the dependencies defined in `pom.xml`.

### 5. Run the Application

Run:

```text
App.java
```

The application will connect to the MySQL database through Hibernate and perform the configured employee management operations.

## 📚 Concepts Demonstrated

* Java OOP
* Classes and Objects
* Encapsulation
* Entity Mapping
* Hibernate ORM
* Hibernate Configuration
* MySQL Database Connectivity
* CRUD Operations
* Maven Dependency Management
* Exception Handling

## 🎯 Project Objective

The main objective of this project is to gain practical experience in building a Java application that interacts with a relational database using **Hibernate ORM** and **MySQL**, while managing dependencies with **Maven**.

## 👨‍💻 Author

**Shaik Khaja**

Java | Hibernate | MySQL | Maven | Full Stack Development

---

⭐ If you found this project useful, consider giving it a star!
