# Super-Mario-Web-Shop
Full-stack webshop built with PHP, MySQL, and Bootstrap. Includes user authentication, product catalog with categories, shopping cart, checkout system, and admin dashboard for managing products, categories, and orders.


# PHP Webshop

A simple **full-stack webshop application** built with **PHP, MySQL, Bootstrap, and XAMPP**.
The project demonstrates core concepts of backend development such as session management, database interaction using PDO, and a basic admin management system.

## Features

### User Features

* User login system with role-based access (Admin / User)
* Product browsing with category filtering
* Shopping cart using PHP sessions
* Checkout system with order creation
* Order history for users
* Responsive product layout using Bootstrap

### Admin Features

* Manage products (create, edit, delete)
* Manage categories
* View and manage orders
* Update order status (Pending / Completed / Cancelled)

### Order System

* Checkout with delivery information and payment method
* Orders stored in a relational MySQL database
* Order items stored separately for scalability
* Transaction handling using PDO

## Technologies Used

* **PHP**
* **MySQL**
* **PDO (PHP Data Objects)**
* **Bootstrap 5**
* **HTML / CSS**
* **JavaScript**
* **XAMPP (Local Development Environment)**

## Database Structure

Main tables used in the project:

* `products` – product information
* `categories` – product categories
* `orders` – order information
* `order_items` – ordered products
* `users` (simulated via static login data)

The project demonstrates relational database design and secure database queries using prepared statements.

## Security Concepts

* Session-based authentication
* Role-based access control
* Prepared SQL statements (PDO) to prevent SQL injection
* Output sanitization using `htmlspecialchars()` to prevent XSS

## Project Purpose

This project was created as a **learning project to practice backend web development with PHP and MySQL**.
It focuses on building a functional e-commerce workflow including authentication, product management, shopping cart functionality, and order processing.

## Setup

1. Install **XAMPP**
2. Clone the repository
3. Move the project into the `htdocs` folder
4. Start **Apache** and **MySQL**
5. Import the database via **phpMyAdmin**
6. Open in browser:

```
http://localhost/your-project-folder
```

## Demo Accounts

Example login accounts included in the project:

Admin

```
username: admin
password: admin123
```

User

```
username: user
password: user123
```

## Author

Created as a project to practice **PHP full-stack web development and database-driven applications**.
