# 🧪 Laravel CRUD Lab Report

> **Course:**  Android and web Application Development sessional 
> **Topic:** Implementation of CRUD Operations in Laravel with MySQL Database (XAMPP)

---

## 👩‍💻 Student Information

| Field | Details |
|-------|---------|
| **Name** | Ivana Islam |
| **Student ID** | 2304034 |
| **Department** | Cyber Security Engineering |
| **University** | University of Frontier Technology, Bangladesh (UFTB) |

---

## 📌 About This Lab

This lab report covers the complete implementation of **CRUD (Create, Read, Update, Delete)** operations using the **Laravel PHP framework** connected to a **MySQL database** running on **XAMPP**.

The project follows Laravel's **MVC (Model-View-Controller)** architecture and demonstrates how data can be created, displayed, modified, and deleted through a web interface — with all changes verified directly in **phpMyAdmin**.

---

## 🛠️ Tools & Technologies

| Tool | Version |
|------|---------|
| Laravel Framework | v13.15.0 |
| PHP | v8.5.7 |
| XAMPP (Apache + MySQL) | v3.3.0 |
| MariaDB | 10.4.32 |
| phpMyAdmin | v5.2.1 |
| Visual Studio Code | Latest |
| OS | Windows 11 |

---

## 📂 Project Structure
app/

├── Http/

│   └── Controllers/

│       └── StudentController.php   # CRUD logic

├── Models/

│   └── Student.php                 # Eloquent Model

database/

└── migrations/

└── xxxx_create_students_table.php  # Database schema

resources/

└── views/

└── students/

├── index.blade.php         # List all students (Read)

├── create.blade.php        # Add new student (Create)

└── edit.blade.php          # Edit student (Update)

routes/

└── web.php                         # Resource routes

.env                                # Database configuration
---

## ✅ CRUD Operations Implemented

| Operation | HTTP Method | Route | Description |
|-----------|-------------|-------|-------------|
| **Create** | POST | `/students` | Add a new student record |
| **Read** | GET | `/students` | Display all student records |
| **Update** | PUT | `/students/{id}` | Edit an existing student record |
| **Delete** | DELETE | `/students/{id}` | Remove a student record |

---

## ⚙️ Setup Summary

1. Started **MySQL server** via XAMPP
2. Created **`laravel`** database in phpMyAdmin
3. Configured **`.env`** file with MySQL credentials
4. Generated Model, Migration & Controller using:
```bash
   php artisan make:model Student -mcr
```
5. Ran migrations:
```bash
   php artisan config:clear
   php artisan migrate
```
6. Built Blade views for Create, Read, Update, Delete
7. Tested all operations in browser and verified in **phpMyAdmin**

---

## 📸 Screenshots

All implementation screenshots are included in the full lab report file uploaded in this repository.

---

## 📄 Full Lab Report

📥 [Click here to download / view the full lab report](./Laravel_CRUD_Full_Lab_Report.pdf)

---

> *Submitted as part of the  Android and web Application Development sessional   — Cyber Security Engineering Department, UFTB*
