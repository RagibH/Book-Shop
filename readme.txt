# Book Shop Management System

This is a PHP-based Online Book Shop Management System developed for academic and learning purposes. The project allows users to browse books, view categories, and manage products through an admin panel. It uses a MySQL database for storing book, category, and user information.

## 🔹 Technologies Used

- PHP
- MySQL
- HTML5
- CSS3
- JavaScript
- Bootstrap
- jQuery
- Summernote Editor

## 🔹 Requirements

- XAMPP / WAMP / MAMP
- PHP 7.x or higher
- MySQL
- A modern web browser
- A text editor (VS Code, Notepad++, Sublime Text, etc.)

## 🔹 Setup Instructions (Localhost)

1. Clone the repository:
git clone https://github.com/RagibH/Book-Shop.git

Or download the ZIP file and extract it.

2. Move the project folder to your local server root:

XAMPP (Windows):
C:\xampp\htdocs\

WAMP:
C:\wamp64\www\

MAMP (macOS):
/Applications/MAMP/htdocs/

3. Start Apache and MySQL from XAMPP / WAMP / MAMP control panel.

4. Open phpMyAdmin:
http://localhost/phpmyadmin

5. Create a database named:
book_shop_db

6. Import the database:
- Select book_shop_db
- Click Import
- Choose book_shop_db.sql (provided in the project)
- Click Go

7. Run the project in your browser:
http://localhost/Book-Shop/

## 🔐 Admin Login Details

Username: admin  
Password: admin123

## 🔹 Project Structure

Book-Shop/
├── plugins/
├── uploads/
├── sql/
│   └── book_shop_db.sql
├── products.php
├── registration.php
├── view_product.php
├── view_categories.php
├── _index.html
├── README.md

## ⚠️ Notes

- This project is intended for local use only.
- GitHub Pages does not support PHP or MySQL, so this project cannot be hosted live on GitHub.
- The repository is maintained for academic submission and learning purposes.

## ✅ Disclaimer

This project is used for educational purposes only. Credits belong to the original source where applicable.
