# dream-home-finder
A dynamic Real Estate Marketplace built with PHP and MySQL. Features property listings, admin management, and efficient database handling for buying and selling homes.
# 🏠 DreamHomes - Real Estate Management System

## 📖 Project Overview
DreamHomes is a robust web-based application designed to facilitate property trading. Built using **PHP and MySQL**, this system allows users to browse properties, contact agents, and list their own real estate. It leverages a relational database to efficiently manage property data, user profiles, and inquiry records.

## 🚀 Key Features
* **Dynamic Content:** Property listings are fetched directly from the MySQL database.
* **Advanced Search:** Users can filter homes by price, location, and category using SQL queries.
* **Admin Panel:** Complete control to Add, Edit, or Delete (CRUD) property listings.
* **User Authentication:** Secure login/signup system for buyers and sellers.
* **Database Management:** Optimized database schema for fast data retrieval.
* **Responsive UI:** Clean interface built with HTML, CSS, and JavaScript.

## 🛠️ Technology Stack
* **Frontend:** HTML5, CSS3, JavaScript
* **Backend:** PHP
* **Database:** MySQL (Relational Database)
* **Server:** Apache (XAMPP/WAMP)

## 🗄️ Database Structure
The project uses a normalized MySQL database with the following key tables:
* `users` - Stores admin and user credentials.
* `properties` - Contains details like price, address, image paths, and description.
* `categories` - Manages property types (Apartment, Villa, Commercial).

## ⚙️ How to Run Locally
1. **Download:** Clone this repository or download the ZIP file.
2. **Database Setup:**
   * Open **phpMyAdmin** (http://localhost/phpmyadmin).
   * Create a new database named `real_estate_db`.
   * Import the `database.sql` file located in the `db/` folder of this project.
3. **Configuration:**
   * Open the `config.php` (or `db_connect.php`) file.
   * Ensure the database credentials (username/password) match your local setup.
4. **Run:**
   * Move the project folder to `htdocs` (for XAMPP).
   * Open your browser and go to `http://localhost/your-folder-name`.

---
*Developed by [Your Name]*
