# DN3.0_Exercises
This repository  includes weekly assignment solutions of Cognizzant Java FSE Deep Skilling stage.

**#DSA**
**Week 1  Java class file solution of assessment of DSA and Principles and Patterns**
**#Exercise 1: Inventory Management System**
**Scenario:** 
You are developing an inventory management system for a warehouse. Efficient data storage and retrieval are crucial.
**Steps:**
1.	Understand the Problem:
o	Explain why data structures and algorithms are essential in handling large inventories.
o	Discuss the types of data structures suitable for this problem.
**2.	Setup:**
o	Create a new project for the inventory management system.
**3.	Implementation:**
o	Define a class Product with attributes like productId, productName, quantity, and price.
o	Choose an appropriate data structure to store the products (e.g., ArrayList, HashMap).
o	Implement methods to add, update, and delete products from the inventory.
**4.	Analysis:**
o	Analyze the time complexity of each operation (add, update, delete) in your chosen data structure.
o	Discuss how you can optimize these operations.

****Exercise 2: E-commerce Platform Search Function
Scenario: ****
You are working on the search functionality of an e-commerce platform. The search needs to be optimized for fast performance.
**Steps:**
**1.	Understand Asymptotic Notation:**
o	Explain Big O notation and how it helps in analyzing algorithms.
o	Describe the best, average, and worst-case scenarios for search operations.
2.	Setup:
o	Create a class Product with attributes for searching, such as productId, productName, and category.
**3.	Implementation:**
o	Implement linear search and binary search algorithms.
o	Store products in an array for linear search and a sorted array for binary search.
**4.	Analysis:**
o	Compare the time complexity of linear and binary search algorithms.
o	Discuss which algorithm is more suitable for your platform and why.

**Exercise 3: Sorting Customer Orders
Scenario: **
You are tasked with sorting customer orders by their total price on an e-commerce platform. This helps in prioritizing high-value orders.
**Steps:**
1.	Understand Sorting Algorithms:
o	Explain different sorting algorithms (Bubble Sort, Insertion Sort, Quick Sort, Merge Sort).
**2.	Setup:**
o	Create a class Order with attributes like orderId, customerName, and totalPrice.
**3.	Implementation:**
o	Implement Bubble Sort to sort orders by totalPrice.
o	Implement Quick Sort to sort orders by totalPrice.
**4.	Analysis:**
o	Compare the performance (time complexity) of Bubble Sort and Quick Sort.
o	Discuss why Quick Sort is generally preferred over Bubble Sort.

**Exercise 4: Employee Management System
Scenario: **
You are developing an employee management system for a company. Efficiently managing employee records is crucial.
**Steps:**
1.	Understand Array Representation:
o	Explain how arrays are represented in memory and their advantages.
**2.	Setup:**
o	Create a class Employee with attributes like employeeId, name, position, and salary.
3.	Implementation:
o	Use an array to store employee records.
o	Implement methods to add, search, traverse, and delete employees in the array.
**4.	Analysis:**
o	Analyze the time complexity of each operation (add, search, traverse, delete).
o	Discuss the limitations of arrays and when to use them.
**
Exercise 5: Task Management System
Scenario: **
You are developing a task management system where tasks need to be added, deleted, and traversed efficiently.
Steps:
**1.	Understand Linked Lists:**
o	Explain the different types of linked lists (Singly Linked List, Doubly Linked List).
**2.	Setup:**
o	Create a class Task with attributes like taskId, taskName, and status.
**3.	Implementation:**
o	Implement a singly linked list to manage tasks.
o	Implement methods to add, search, traverse, and delete tasks in the linked list.
**4.	Analysis:**
o	Analyze the time complexity of each operation.
o	Discuss the advantages of linked lists over arrays for dynamic data.

**Exercise 6: Library Management System
Scenario: **
You are developing a library management system where users can search for books by title or author.
**Steps:**
1.	Understand Search Algorithms:
o	Explain linear search and binary search algorithms.
**2.	Setup:**
o	Create a class Book with attributes like bookId, title, and author.
**3.	Implementation:**
o	Implement linear search to find books by title.
o	Implement binary search to find books by title (assuming the list is sorted).
**4.	Analysis:**
o	Compare the time complexity of linear and binary search.
o	Discuss when to use each algorithm based on the data set size and order.

**Exercise 7: Financial Forecasting
Scenario:** 
You are developing a financial forecasting tool that predicts future values based on past data.
**Steps:**
1.	Understand Recursive Algorithms:
o	Explain the concept of recursion and how it can simplify certain problems.
**2.	Setup:**
o	Create a method to calculate the future value using a recursive approach.
**3.	Implementation:**
o	Implement a recursive algorithm to predict future values based on past growth rates.
**4.	Analysis:**
o	Discuss the time complexity of your recursive algorithm.
o	Explain how to optimize the recursive solution to avoid excessive computation.**


#DESIGN PRINCIPLES AND PATTERNS**

**
Exercise 1: Implementing the Singleton Pattern**
Scenario: 
You need to ensure that a logging utility class in your application has only one instance throughout the application lifecycle to ensure consistent logging.
Steps:
1.	Create a New Java Project:
o	Create a new Java project named SingletonPatternExample.
2.	Define a Singleton Class:
o	Create a class named Logger that has a private static instance of itself.
o	Ensure the constructor of Logger is private.
o	Provide a public static method to get the instance of the Logger class.
3.	Implement the Singleton Pattern:
o	Write code to ensure that the Logger class follows the Singleton design pattern.
4.	Test the Singleton Implementation:
o	Create a test class to verify that only one instance of Logger is created and used across the application.


**Exercise 2: Implementing the Factory Method Pattern**
Scenario: 
You are developing a document management system that needs to create different types of documents (e.g., Word, PDF, Excel). Use the Factory Method Pattern to achieve this.
Steps:
1.	Create a New Java Project:
o	Create a new Java project named FactoryMethodPatternExample.
2.	Define Document Classes:
o	Create interfaces or abstract classes for different document types such as WordDocument, PdfDocument, and ExcelDocument.
3.	Create Concrete Document Classes:
o	Implement concrete classes for each document type that implements or extends the above interfaces or abstract classes.
4.	Implement the Factory Method:
o	Create an abstract class DocumentFactory with a method createDocument().
o	Create concrete factory classes for each document type that extends DocumentFactory and implements the createDocument() method.
5.	Test the Factory Method Implementation:
o	Create a test class to demonstrate the creation of different document types using the factory method.


**Exercise 3: Implementing the Builder Pattern**
Scenario: 
You are developing a system to create complex objects such as a Computer with multiple optional parts. Use the Builder Pattern to manage the construction process.
Steps:
1.	Create a New Java Project:
o	Create a new Java project named BuilderPatternExample.
2.	Define a Product Class:
o	Create a class Computer with attributes like CPU, RAM, Storage, etc.
3.	Implement the Builder Class:
o	Create a static nested Builder class inside Computer with methods to set each attribute.
o	Provide a build() method in the Builder class that returns an instance of Computer.
4.	Implement the Builder Pattern:
o	Ensure that the Computer class has a private constructor that takes the Builder as a parameter.
5.	Test the Builder Implementation:
o	Create a test class to demonstrate the creation of different configurations of Computer using the Builder pattern.


**Exercise 4: Implementing the Adapter Pattern
Scenario: **
You are developing a payment processing system that needs to integrate with multiple third-party payment gateways with different interfaces. Use the Adapter Pattern to achieve this.
Steps:
1.	Create a New Java Project:
o	Create a new Java project named AdapterPatternExample.
2.	Define Target Interface:
o	Create an interface PaymentProcessor with methods like processPayment().
3.	Implement Adaptee Classes:
o	Create classes for different payment gateways with their own methods.
4.	Implement the Adapter Class:
o	Create an adapter class for each payment gateway that implements PaymentProcessor and translates the calls to the gateway-specific methods.
5.	Test the Adapter Implementation:
o	Create a test class to demonstrate the use of different payment gateways through the adapter.


**Exercise 5: Implementing the Decorator Pattern**
Scenario: 
You are developing a notification system where notifications can be sent via multiple channels (e.g., Email, SMS). Use the Decorator Pattern to add functionalities dynamically.
Steps:
1.	Create a New Java Project:
o	Create a new Java project named DecoratorPatternExample.
2.	Define Component Interface:
o	Create an interface Notifier with a method send().
3.	Implement Concrete Component:
o	Create a class EmailNotifier that implements Notifier.
4.	Implement Decorator Classes:
o	Create abstract decorator class NotifierDecorator that implements Notifier and holds a reference to a Notifier object.
o	Create concrete decorator classes like SMSNotifierDecorator, SlackNotifierDecorator that extend NotifierDecorator.
5.	Test the Decorator Implementation:
o	Create a test class to demonstrate sending notifications via multiple channels using decorators.


**Exercise 6: Implementing the Proxy Pattern
Scenario: **
You are developing an image viewer application that loads images from a remote server. Use the Proxy Pattern to add lazy initialization and caching.
Steps:
1.	Create a New Java Project:
o	Create a new Java project named ProxyPatternExample.
2.	Define Subject Interface:
o	Create an interface Image with a method display().
3.	Implement Real Subject Class:
o	Create a class RealImage that implements Image and loads an image from a remote server.
4.	Implement Proxy Class:
o	Create a class ProxyImage that implements Image and holds a reference to RealImage.
o	Implement lazy initialization and caching in ProxyImage.
5.	Test the Proxy Implementation:
o	Create a test class to demonstrate the use of ProxyImage to load and display images.


**Exercise 7: Implementing the Observer Pattern
Scenario: **
You are developing a stock market monitoring application where multiple clients need to be notified whenever stock prices change. Use the Observer Pattern to achieve this.
Steps:
1.	Create a New Java Project:
o	Create a new Java project named ObserverPatternExample.
2.	Define Subject Interface:
o	Create an interface Stock with methods to register, deregister, and notify observers.
3.	Implement Concrete Subject:
o	Create a class StockMarket that implements Stock and maintains a list of observers.
4.	Define Observer Interface:
o	Create an interface Observer with a method update().
5.	Implement Concrete Observers:
o	Create classes MobileApp, WebApp that implement Observer.
6.	Test the Observer Implementation:
o	Create a test class to demonstrate the registration and notification of observers.

**
Exercise 8: Implementing the Strategy Pattern**
Scenario: 
You are developing a payment system where different payment methods (e.g., Credit Card, PayPal) can be selected at runtime. Use the Strategy Pattern to achieve this.
Steps:
1.	Create a New Java Project:
o	Create a new Java project named StrategyPatternExample.
2.	Define Strategy Interface:
o	Create an interface PaymentStrategy with a method pay().
3.	Implement Concrete Strategies:
o	Create classes CreditCardPayment, PayPalPayment that implement PaymentStrategy.
4.	Implement Context Class:
o	Create a class PaymentContext that holds a reference to PaymentStrategy and a method to execute the strategy.
5.	Test the Strategy Implementation:
o	Create a test class to demonstrate selecting and using different payment strategies.


**Exercise 9: Implementing the Command Pattern**
Scenario: You are developing a home automation system where commands can be issued to turn devices on or off. Use the Command Pattern to achieve this.
Steps:
1.	Create a New Java Project:
o	Create a new Java project named CommandPatternExample.
2.	Define Command Interface:
o	Create an interface Command with a method execute().
3.	Implement Concrete Commands:
o	Create classes LightOnCommand, LightOffCommand that implement Command.
4.	Implement Invoker Class:
o	Create a class RemoteControl that holds a reference to a Command and a method to execute the command.
5.	Implement Receiver Class:
o	Create a class Light with methods to turn on and off.
6.	Test the Command Implementation:
o	Create a test class to demonstrate issuing commands using the RemoteControl.


**Exercise 10: Implementing the MVC Pattern**
Scenario: 
You are developing a simple web application for managing student records using the MVC pattern.
Steps:
1.	Create a New Java Project:
o	Create a new Java project named MVCPatternExample.
2.	Define Model Class:
o	Create a class Student with attributes like name, id, and grade.
3.	Define View Class:
o	Create a class StudentView with a method displayStudentDetails().
4.	Define Controller Class:
o	Create a class StudentController that handles the communication between the model and the view.
5.	Test the MVC Implementation:
o	Create a main class to demonstrate creating a Student, updating its details using StudentController, and displaying them using StudentView.


**Exercise 11: Implementing Dependency Injection**
Scenario: 
You are developing a customer management application where the service class depends on a repository class. Use Dependency Injection to manage these dependencies.
Steps:
1.	Create a New Java Project:
o	Create a new Java project named DependencyInjectionExample.
2.	Define Repository Interface:
o	Create an interface CustomerRepository with methods like findCustomerById().
3.	Implement Concrete Repository:
o	Create a class CustomerRepositoryImpl that implements CustomerRepository.
4.	Define Service Class:
o	Create a class CustomerService that depends on CustomerRepository.
5.	Implement Dependency Injection:
o	Use constructor injection to inject CustomerRepository into CustomerService.
6.	Test the Dependency Injection Implementation:
o	Create a main class to demonstrate creating a CustomerService with CustomerRepositoryImpl and using it to find a customer.


**
Week 2- PLSQL & SPRING CORE**

**Exercise 1: Control Structures**

Scenario 1: The bank wants to apply a discount to loan interest rates for customers above 60 years old.
o	Question: Write a PL/SQL block that loops through all customers, checks their age, and if they are above 60, apply a 1% discount to their current loan interest rates.
Scenario 2: A customer can be promoted to VIP status based on their balance.
o	Question: Write a PL/SQL block that iterates through all customers and sets a flag IsVIP to TRUE for those with a balance over $10,000.
Scenario 3: The bank wants to send reminders to customers whose loans are due within the next 30 days.
o	Question: Write a PL/SQL block that fetches all loans due in the next 30 days and prints a reminder message for each customer.

Exercise 2: Error Handling

Scenario 1: Handle exceptions during fund transfers between accounts.
o	Question: Write a stored procedure SafeTransferFunds that transfers funds between two accounts. Ensure that if any error occurs (e.g., insufficient funds), an appropriate error message is logged and the transaction is rolled back.

Scenario 2: Manage errors when updating employee salaries.
o	Question: Write a stored procedure UpdateSalary that increases the salary of an employee by a given percentage. If the employee ID does not exist, handle the exception and log an error message.
Scenario 3: Ensure data integrity when adding a new customer.
o	Question: Write a stored procedure AddNewCustomer that inserts a new customer into the Customers table. If a customer with the same ID already exists, handle the exception by logging an error and preventing the insertion.

Exercise 3: Stored Procedures

Scenario 1: The bank needs to process monthly interest for all savings accounts.
o	Question: Write a stored procedure ProcessMonthlyInterest that calculates and updates the balance of all savings accounts by applying an interest rate of 1% to the current balance.

Scenario 2: The bank wants to implement a bonus scheme for employees based on their performance.
o	Question: Write a stored procedure UpdateEmployeeBonus that updates the salary of employees in a given department by adding a bonus percentage passed as a parameter.

Scenario 3: Customers should be able to transfer funds between their accounts.
o	Question: Write a stored procedure TransferFunds that transfers a specified amount from one account to another, checking that the source account has sufficient balance before making the transfer.

Exercise 4: Functions

Scenario 1: Calculate the age of customers for eligibility checks.
o	Question: Write a function CalculateAge that takes a customer's date of birth as input and returns their age in years.

Scenario 2: The bank needs to compute the monthly installment for a loan.
o	Question: Write a function CalculateMonthlyInstallment that takes the loan amount, interest rate, and loan duration in years as input and returns the monthly installment amount.

Scenario 3: Check if a customer has sufficient balance before making a transaction.
o	Question: Write a function HasSufficientBalance that takes an account ID and an amount as input and returns a boolean indicating whether the account has at least the specified amount.

Exercise 5: Triggers

Scenario 1: Automatically update the last modified date when a customer's record is updated.
o	Question: Write a trigger UpdateCustomerLastModified that updates the LastModified column of the Customers table to the current date whenever a customer's record is updated.
Scenario 2: Maintain an audit log for all transactions.
o	Question: Write a trigger LogTransaction that inserts a record into an AuditLog table whenever a transaction is inserted into the Transactions table.

Scenario 3: Enforce business rules on deposits and withdrawals.
o	Question: Write a trigger CheckTransactionRules that ensures withdrawals do not exceed the balance and deposits are positive before inserting a record into the Transactions table.





Exercise 6: Cursors

Scenario 1: Generate monthly statements for all customers.
o	Question: Write a PL/SQL block using an explicit cursor GenerateMonthlyStatements that retrieves all transactions for the current month and prints a statement for each customer.
Scenario 2: Apply annual fee to all accounts.
o	Question: Write a PL/SQL block using an explicit cursor ApplyAnnualFee that deducts an annual maintenance fee from the balance of all accounts.
Scenario 3: Update the interest rate for all loans based on a new policy.
o	Question: Write a PL/SQL block using an explicit cursor UpdateLoanInterestRates that fetches all loans and updates their interest rates based on the new policy.

Exercise 7: Packages

Scenario 1: Group all customer-related procedures and functions into a package.
o	Question: Create a package CustomerManagement with procedures for adding a new customer, updating customer details, and a function to get customer balance.
Scenario 2: Create a package to manage employee data.
o	Question: Write a package EmployeeManagement with procedures to hire new employees, update employee details, and a function to calculate annual salary.
Scenario 3: Group all account-related operations into a package.
o	Question: Create a package AccountOperations with procedures for opening a new account, closing an account, and a function to get the total balance of a customer across all accounts.

Schema to be Created

CREATE TABLE Customers (
    CustomerID NUMBER PRIMARY KEY,
    Name VARCHAR2(100),
    DOB DATE,
    Balance NUMBER,
    LastModified DATE
);

CREATE TABLE Accounts (
    AccountID NUMBER PRIMARY KEY,
    CustomerID NUMBER,
    AccountType VARCHAR2(20),
    Balance NUMBER,
    LastModified DATE,
    FOREIGN KEY (CustomerID) REFERENCES Customers(CustomerID)
);

CREATE TABLE Transactions (
    TransactionID NUMBER PRIMARY KEY,
    AccountID NUMBER,
    TransactionDate DATE,
    Amount NUMBER,
    TransactionType VARCHAR2(10),
    FOREIGN KEY (AccountID) REFERENCES Accounts(AccountID)
);

CREATE TABLE Loans (
    LoanID NUMBER PRIMARY KEY,
    CustomerID NUMBER,
    LoanAmount NUMBER,
    InterestRate NUMBER,
    StartDate DATE,
    EndDate DATE,
    FOREIGN KEY (CustomerID) REFERENCES Customers(CustomerID)
);

CREATE TABLE Employees (
    EmployeeID NUMBER PRIMARY KEY,
    Name VARCHAR2(100),
    Position VARCHAR2(50),
    Salary NUMBER,
    Department VARCHAR2(50),
    HireDate DATE
); 

Example Scripts for Sample Data Insertion

INSERT INTO Customers (CustomerID, Name, DOB, Balance, LastModified)
VALUES (1, 'John Doe', TO_DATE('1985-05-15', 'YYYY-MM-DD'), 1000, SYSDATE);

INSERT INTO Customers (CustomerID, Name, DOB, Balance, LastModified)
VALUES (2, 'Jane Smith', TO_DATE('1990-07-20', 'YYYY-MM-DD'), 1500, SYSDATE);

INSERT INTO Accounts (AccountID, CustomerID, AccountType, Balance, LastModified)
VALUES (1, 1, 'Savings', 1000, SYSDATE);

INSERT INTO Accounts (AccountID, CustomerID, AccountType, Balance, LastModified)
VALUES (2, 2, 'Checking', 1500, SYSDATE);

INSERT INTO Transactions (TransactionID, AccountID, TransactionDate, Amount, TransactionType)
VALUES (1, 1, SYSDATE, 200, 'Deposit');

INSERT INTO Transactions (TransactionID, AccountID, TransactionDate, Amount, TransactionType)
VALUES (2, 2, SYSDATE, 300, 'Withdrawal');

INSERT INTO Loans (LoanID, CustomerID, LoanAmount, InterestRate, StartDate, EndDate)
VALUES (1, 1, 5000, 5, SYSDATE, ADD_MONTHS(SYSDATE, 60));

INSERT INTO Employees (EmployeeID, Name, Position, Salary, Department, HireDate)
VALUES (1, 'Alice Johnson', 'Manager', 70000, 'HR', TO_DATE('2015-06-15', 'YYYY-MM-DD'));

INSERT INTO Employees (EmployeeID, Name, Position, Salary, Department, HireDate)
VALUES (2, 'Bob Brown', 'Developer', 60000, 'IT', TO_DATE('2017-03-20', 'YYYY-MM-DD'));


**SPRING CORE MAVEN**
Exercise 1: Configuring a Basic Spring Application
Scenario: 
Your company is developing a web application for managing a library. You need to use the Spring Framework to handle the backend operations.
Steps:
1.	Set Up a Spring Project:
o	Create a Maven project named LibraryManagement.
o	Add Spring Core dependencies in the pom.xml file.
2.	Configure the Application Context:
o	Create an XML configuration file named applicationContext.xml in the src/main/resources directory.
o	Define beans for BookService and BookRepository in the XML file.
3.	Define Service and Repository Classes:
o	Create a package com.library.service and add a class BookService.
o	Create a package com.library.repository and add a class BookRepository.
4.	Run the Application:
o	Create a main class to load the Spring context and test the configuration.
Exercise 2: Implementing Dependency Injection
Scenario: 
In the library management application, you need to manage the dependencies between the BookService and BookRepository classes using Spring's IoC and DI.
Steps:
1.	Modify the XML Configuration:
o	Update applicationContext.xml to wire BookRepository into BookService.
2.	Update the BookService Class:
o	Ensure that BookService class has a setter method for BookRepository.
3.	Test the Configuration:
o	Run the LibraryManagementApplication main class to verify the dependency injection.



Exercise 3: Implementing Logging with Spring AOP
Scenario: 
The library management application requires logging capabilities to track method execution times.
Steps:
1.	Add Spring AOP Dependency:
o	Update pom.xml to include Spring AOP dependency.
2.	Create an Aspect for Logging:
o	Create a package com.library.aspect and add a class LoggingAspect with a method to log execution times.
3.	Enable AspectJ Support:
o	Update applicationContext.xml to enable AspectJ support and register the aspect.
4.	Test the Aspect:
o	Run the LibraryManagementApplication main class and observe the console for log messages indicating method execution times.
Exercise 4: Creating and Configuring a Maven Project
Scenario: 
You need to set up a new Maven project for the library management application and add Spring dependencies.
Steps:
1.	Create a New Maven Project:
o	Create a new Maven project named LibraryManagement.
2.	Add Spring Dependencies in pom.xml:
o	Include dependencies for Spring Context, Spring AOP, and Spring WebMVC.
3.	Configure Maven Plugins:
o	Configure the Maven Compiler Plugin for Java version 1.8 in the pom.xml file.




Exercise 5: Configuring the Spring IoC Container
Scenario: 
The library management application requires a central configuration for beans and dependencies.
Steps:
1.	Create Spring Configuration File:
o	Create an XML configuration file named applicationContext.xml in the src/main/resources directory.
o	Define beans for BookService and BookRepository in the XML file.
2.	Update the BookService Class:
o	Ensure that the BookService class has a setter method for BookRepository.
3.	Run the Application:
o	Create a main class to load the Spring context and test the configuration.
 
Exercise 6: Configuring Beans with Annotations
Scenario: 
You need to simplify the configuration of beans in the library management application using annotations.
Steps:
1.	Enable Component Scanning:
o	Update applicationContext.xml to include component scanning for the com.library package.
2.	Annotate Classes:
o	Use @Service annotation for the BookService class.
o	Use @Repository annotation for the BookRepository class.
3.	Test the Configuration:
o	Run the LibraryManagementApplication main class to verify the annotation-based configuration.



Exercise 7: Implementing Constructor and Setter Injection
Scenario: 
The library management application requires both constructor and setter injection for better control over bean initialization.
Steps:
1.	Configure Constructor Injection:
o	Update applicationContext.xml to configure constructor injection for BookService.
2.	Configure Setter Injection:
o	Ensure that the BookService class has a setter method for BookRepository and configure it in applicationContext.xml.
3.	Test the Injection:
o	Run the LibraryManagementApplication main class to verify both constructor and setter injection.
Exercise 8: Implementing Basic AOP with Spring
Scenario: 
The library management application requires basic AOP functionality to separate cross-cutting concerns like logging and transaction management.
Steps:
1.	Define an Aspect:
o	Create a package com.library.aspect and add a class LoggingAspect.
2.	Create Advice Methods:
o	Define advice methods in LoggingAspect for logging before and after method execution.
3.	Configure the Aspect:
o	Update applicationContext.xml to register the aspect and enable AspectJ auto-proxying.
4.	Test the Aspect:
o	Run the LibraryManagementApplication main class to verify the AOP functionality.




Exercise 9: Creating a Spring Boot Application
Scenario: 
You need to create a Spring Boot application for the library management system to simplify configuration and deployment.
Steps:
1.	Create a Spring Boot Project:
o	Use Spring Initializr to create a new Spring Boot project named LibraryManagement.
2.	Add Dependencies:
o	Include dependencies for Spring Web, Spring Data JPA, and H2 Database.
3.	Create Application Properties:
o	Configure database connection properties in application.properties.
4.	Define Entities and Repositories:
o	Create Book entity and BookRepository interface.
5.	Create a REST Controller:
o	Create a BookController class to handle CRUD operations.
6.	Run the Application:
o	Run the Spring Boot application and test the REST endpoints.



