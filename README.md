

#Supermarket Management System

Overview

This Supermarket Management System is a desktop-based application developed in Java using Swing for the GUI and MySQL as the backend database. The project is designed to help supermarkets manage products, employees, and categories, providing a simple and intuitive interface for adding, updating, and deleting records from the database. The system interacts with the MySQL database using JDBC.

Features

Login System: Only registered employees can access the system.

Employee Management:

Add new employees

Update employee passwords

Delete employee records


Product Management:

Add new products

Update product quantities

Delete products


Category Management:

Manage product categories (add new categories, delete categories)


MySQL Database Integration: The application stores and retrieves data from a MySQL database to ensure data persistence.


Technologies Used

Java (JDK 8+)

Java Swing for creating the graphical user interface (GUI)

MySQL for data storage

JDBC (Java Database Connectivity) for database interaction

NetBeans IDE (version 22)


Database Structure

employees table:

EID (Employee ID)

EmployeeName

Password


products table:

PID (Product ID)

ProductName

Quantity


categories table:

CID (Category ID)

Category



How to Set Up

1. Clone the Repository:

git clone https://github.com/your-username/supermarket-management-system.git


2. Set up the MySQL Database:

Create a new MySQL database named supermarket.

Import the database schema from the provided SQL file located in the database folder of the repository.

Ensure the MySQL server is running and accessible.



3. Configure the JDBC Connection:

Update the DBConnection.java file with your MySQL credentials:

String url = "jdbc:mysql://localhost:3306/supermarket";
String user = "your-username";
String password = "your-password";



4. Run the Project:

Open the project in NetBeans IDE.

Build and run the project to launch the application.




Screenshots

Include some screenshots of the Login page, Employee Management page, Product Management page, etc.

Future Improvements

Add detailed reporting features.

Implement product stock tracking.

Improve the user interface with modern UI design.


Contributing

Feel free to fork this project and submit pull requests. Contributions are welcome to improve the features or add new functionalities!

License

This project is licensed under the MIT License. See the LICENSE file for details.


---

You can adjust the content as per your preferences and add any additional sections you think might be useful!

