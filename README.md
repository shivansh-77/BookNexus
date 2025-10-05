
# 📚 eLibrary Management System

A simple and functional **Library Management System** built with PHP and MySQL.  
It allows administrators to manage authors, publishers, books, categories, and registered students — all through a clean web interface.

---

## 🖥️ Project Overview

This project is designed for managing small to medium-sized libraries digitally.  
The dashboard provides quick access to key metrics such as:

- Total Authors Listed  
- Total Publishers Listed  
- Categories Listed  
- Books Listed  
- Registered Students  
- Books Issued  

Everything is managed from an easy-to-use admin panel.

---

## 🧱 Tech Stack

- **Frontend:** HTML, CSS, Bootstrap  
- **Backend:** PHP (Procedural)  
- **Database:** MySQL  
- **Server:** XAMPP / WAMP (Localhost Environment)

---

## ⚙️ Installation Steps

### 1. Setup the Project

1. Download or clone this repository:
   ```bash
   git clone https://github.com/<shivansh-77>/library-system.git
````

2. Extract the project inside:

   ```
   C:/xampp/htdocs/
   ```

   or

   ```
   C:/wamp/www/
   ```

---

### 2. Database Configuration

1. Open **phpMyAdmin** from your localhost control panel.
2. Create a new database named:

   ```sql
   library_system
   ```
3. Import the SQL file located in:

   ```
   sql/library_system.sql
   ```
4. Open `config.php` inside the project folder and update your database credentials:

   ```php
   $conn = mysqli_connect("localhost", "root", "", "library_system");
   ```

   > Change the username and password if needed for your environment.

---

## 🚀 Run the Project

1. Start **Apache** and **MySQL** from **XAMPP / WAMP**.
2. Open your browser and visit:

   ```
   http://localhost/library-system/
   ```
3. Log in using the default credentials:

   ```
   Login ID: admin
   Password: admin
   ```

---

## 📂 Folder Structure

```
library-system/
│
├── css/                  # Stylesheets
├── images/               # UI Images
├── sql/                  # Database export file
├── add-author.php
├── add-book.php
├── add-category.php
├── dashboard.php         # Main dashboard (Admin view)
├── config.php            # Database connection setup
├── header.php / footer.php
├── reports.php
├── settings.php
└── ... other PHP modules
```

---

## 🧾 Features

* Admin login authentication
* Add, update, delete authors, publishers, books, and categories
* Register students
* Issue and return books
* View summarized statistics in dashboard
* Basic report generation

---

## 🧑‍💻 Admin Dashboard Preview

The dashboard provides a quick summary of all library activities — authors, publishers, categories, books, registered students, and issued books — in a clean tile-based layout.

---

## 🧠 Future Enhancements

* Add user roles (Admin / Librarian / Student)
* Improve UI using modern frameworks
* Add search and filtering options
* Add email notifications for due books

---

## 🪪 License

This project is open-source and free to use for learning and personal development purposes.

---

**Developed by Shivansh Bajpai with ❤️ for learning PHP & MySQL.**
