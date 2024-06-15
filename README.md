# Java Banking Application

Welcome to the Java Banking Application project! This project simulates a basic banking system with functionalities like account creation, login, balance checking, and money transfer.

## Overview

The project consists of two main classes:

- **bankManagement.java**: Contains methods for managing bank accounts such as creating accounts (`createAccount`), logging in (`loginAccount`), checking balances (`getBalance`), and transferring money (`transferMoney`).
- **bank.java**: Main class to run the banking application, providing a simple console interface for users to create accounts or log in.

## Features

- **Account Creation**: Users can create a new bank account with a unique username and password.
- **Login**: Existing users can log in using their username and password to access account functionalities.
- **Balance Inquiry**: Users can check their account balance.
- **Money Transfer**: Users can transfer money between accounts.

## Technologies Used

- Java
- JDBC for database connectivity (Assumes a relational database setup where `connection.getConnection()` establishes a connection to the database).

## How to Run

1. **Clone the Repository**:

2. **Compile Java Files**:
 
3. **Run the Application**:
4. 
4. **Follow the Console Prompts**:
- Choose option 1 to create a new account or option 2 to log in to an existing account.
- Follow the subsequent prompts to perform desired banking operations.

## Database Setup

- Ensure a MySQL database is set up with the following schema:
```sql
CREATE TABLE customer (
   ac_no INT AUTO_INCREMENT PRIMARY KEY,
   cname VARCHAR(50) NOT NULL UNIQUE,
   balance INT DEFAULT 1000,
   pass_code INT NOT NULL
);


