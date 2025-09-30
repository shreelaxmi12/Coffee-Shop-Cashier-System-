# Coffee-Shop-Cashier-System-
A DBMS project built using PHP &amp; MySQL for managing a coffee shop’s daily transactions, products, and customers.   This system helps automate billing, maintain records, and manage staff efficiently.
Coffee Shop Cashier System


Coffee Shop Cashier System

A *DBMS project* built using *PHP & MySQL* for managing a coffee shop’s daily transactions, products, and customers.  
This system helps automate billing, maintain records, and manage staff efficiently.

Features
User authentication (Admin / Cashier login)  
Product management (add, update, delete items)  
Order & billing system with receipt generation  
Database-driven architecture (MySQL)  
Reports on sales and transactions  
Responsive UI for better usability  

Tech Stack
Frontend: HTML, CSS, JavaScript  
Backend: PHP  
Database: MySQL  
Server:Apache (XAMPP/WAMP/LAMP)  

 Project Structure
 coffee-shop-cashier-system
│── index.php # Entry point
│── config.sample.php # DB config template (replace with your credentials)
│── .htaccess # URL rewriting (if used)
│── /classes # PHP classes for core logic
│── /admin # Admin panel
│── /assets # CSS, JS, images
│── /database
│ └── coffee_shop.sql # Database schema
│── /uploads # (Optional) uploaded images or receipts
│── README.md # Project documentation

2.Move the project folder to your server root:
For XAMPP → htdocs/
For WAMP → www/

3.Import the database:
Open phpMyAdmin
Create a new DB (e.g., coffee_shop)
Import database/coffee_shop.sql

4.Configure database connection:
Rename config.sample.php → config.php
Add your DB username, password, and DB name.

5.Run the project in your browser:
http://localhost/coffee-shop-cashier-system
