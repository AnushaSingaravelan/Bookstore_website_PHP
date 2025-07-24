# 📚 Online Bookstore Website

An online bookstore web application built using **PHP** and **MySQL**. This project allows users to browse books, add them to a cart, and place orders. Admins can manage inventory, view orders, and handle customer information.

---

## 🛠️ Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Tools**: XAMPP / WAMP, phpMyAdmin

---

## 📂 Project Structure

/bookstore
│
├── index.php # Homepage
├── login.php # User login
├── register.php # User registration
├── books.php # Display all books
├── cart.php # Shopping cart
├── checkout.php # Order checkout
├── admin/
│ ├── dashboard.php # Admin panel
│ └── manage_books.php # Book management
├── db.php # Database connection
└── css/
└── style.css # Styling file

## 💾 Database Setup

1. Import the `bookstore.sql` file into your MySQL database using **phpMyAdmin**.
2. Update the database credentials in `db.php`:
```php
$host = "localhost";
$username = "root";
$password = "";
$database = "bookstore";