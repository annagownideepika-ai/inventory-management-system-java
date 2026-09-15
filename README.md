# Inventory Management System

A simple **console-based Inventory Management System** developed using **Java**. The application allows users to manage products, track stock quantities, update prices, search products, and calculate the total value of inventory.

## Features

* Add new products
* View all products
* Search products by name
* Update product stock
* Update product prices
* Delete products
* Calculate total inventory value
* Identify low-stock products
* Automatic product IDs
* Input validation
* Menu-driven console interface

## Technologies Used

* Java
* Object-Oriented Programming
* ArrayList
* Scanner
* Console-based application

## Project Structure

```text
inventory-management-system-java/
├── src/
│   └── InventoryManagementSystem.java
├── README.md
└── .gitignore
```

## Product Details

Each product contains:

| Field      | Description               |
| ---------- | ------------------------- |
| Product ID | Unique product identifier |
| Name       | Product name              |
| Category   | Product category          |
| Quantity   | Available stock           |
| Price      | Price per product         |

## Example Categories

Products can be organized into categories such as:

* Electronics
* Clothing
* Food
* Stationery
* Furniture
* Grocery
* Sports
* Other

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/inventory-management-system-java.git
```

### 2. Navigate to the project

```bash
cd inventory-management-system-java
```

### 3. Compile the program

```bash
javac src/InventoryManagementSystem.java
```

### 4. Run the program

```bash
java -cp src InventoryManagementSystem
```

## Example

```text
======================================
       INVENTORY MANAGEMENT SYSTEM
======================================
1. Add Product
2. View Products
3. Search Product
4. Update Stock
5. Update Price
6. Delete Product
7. Show Inventory Value
8. Show Low Stock Products
9. Exit
======================================
Enter your choice: 1

Enter Product Name: Laptop
Enter Category: Electronics
Enter Quantity: 10
Enter Price: 55000

Product added successfully.
```

## Inventory Value Example

If the inventory contains:

```text
Laptop     Quantity: 10    Price: 55000
Keyboard   Quantity: 20    Price: 1500
```

The application calculates:

```text
Total Inventory Value: 580000.00
```

## Low Stock Example

```text
Enter low stock limit: 5

========== LOW STOCK PRODUCTS ==========
--------------------------------
Product ID : 3
Name       : Mouse
Category   : Electronics
Quantity   : 3
Price      : 800.00
```

## Java Concepts Used

This project demonstrates:

* Classes and Objects
* Constructors
* Methods
* ArrayList
* Loops
* Conditional statements
* Switch statements
* Scanner
* Searching
* Updating objects
* Basic input validation
* CRUD operations

## Future Improvements

The project can be extended with:

* Product update and editing
* Supplier management
* Purchase and sales records
* Automatic stock deduction after sales
* Stock-in and stock-out history
* MySQL database using JDBC
* Login and user authentication
* Barcode/product-code support
* Invoice generation
* Reports and analytics
* GUI using Java Swing or JavaFX
* Spring Boot REST API
* Web-based inventory dashboard

## Learning Objective

This project is useful for practicing **Java fundamentals, OOP concepts, collections, CRUD operations, searching, updating records, and basic inventory calculations**.

## License

This project is intended for educational and learning purposes.
