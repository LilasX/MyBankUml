# BankUml: Banking System Simulation

Welcome to **BankUml**, a Java-based banking application designed to simulate core banking operations such as account management, transactions, and receipts.  

This project demonstrates the use of Object-Oriented Programming (OOP) principles, including **Inheritance**, **Encapsulation**, **Abstraction**, and **Polymorphism**, strictly following the provided UML diagram.

## Features

- **Account Management**: Create and manage multiple types of bank accounts.
- **Transaction Handling**: Simulate payments and generate receipts.
- **UML-Driven Design**: Class structure directly follows the given UML diagram.

## Modifications
This project is an extension of the original **BankUML** project. You can find the previous version here: [Old BankUML Project](https://github.com/M-PERSIC/BankUml).


# How to Run the MyBankUML Software

## 1. Install Spring Boot and MySQL
Install Spring Boot and MySQL on your device.

- Spring Boot (VS Code extension): https://code.visualstudio.com/docs/java/java-spring-boot  
- Spring Boot (direct download): https://docs.spring.io/spring-boot/installing.html  
- MySQL installation: https://dev.mysql.com/doc/refman/8.4/en/installing.html  

Install and configure MySQL according to your operating system.

## 2. Download MySQL Workbench
Use MySQL Workbench to interact with the database and execute queries manually:

- MySQL Workbench: https://dev.mysql.com/doc/workbench/en/wb-installing.html

## 3. Start the MySQL Server
Instructions for starting the MySQL server:

- https://dev.mysql.com/doc/refman/8.4/en/connecting-disconnecting.html

## 4. Create the Database
Use the provided SQL file `mybank_schema.sql` (included in the project) to create the database.

## 5. Configure Application Properties
Open the project directory and navigate to:

/src/main/resources/application.properties

Update the following fields:
```
spring.datasource.username=your-mysql-username
spring.datasource.password=your-mysql-password
```

## 6. Build and Run the Application
From the terminal or command line, run:
```
mvn clean package
mvn spring-boot:run
```

(`mvn clean package` is needed only once.)

## 7. Access the GUI
After the Spring Boot application starts successfully, visit the following URLs:

- Customer Login: http://localhost:8080/gui/customer/customer-login.html  
- Teller Login: http://localhost:8080/gui/teller/teller-login.html  
- Admin Login: http://localhost:8080/gui/admin/admin-login.html  

---

# Test Accounts

## Customer
- **Email:** alice@bank.ca  
- **Password:** pass1234  

## Teller
- **Email:** teller@bank.ca  
- **Password:** pass1234  

## Admin
- **Email:** admin@bank.ca  
- **Password:** pass1234  