# Animal Rescue App 🐾

## Project Overview

The Animal Rescue App is a web-based application developed using PHP and MySQL that helps users report injured or stray animals and allows NGOs or rescue organizations to manage rescue operations efficiently.

The system provides separate login portals for users, NGOs, and administrators. Users can submit rescue reports with images and location details, while NGOs can manage rescue requests and update statuses.


# Features

## User Module

* User Registration and Login
* Submit animal rescue reports
* Upload animal images
* View report status
* User Dashboard

## NGO Module

* NGO Registration and Login
* View rescue reports
* Update rescue request status
* NGO Dashboard

## Admin Module

* Admin Login
* Manage rescue activities
* Monitor reports and users
* Dashboard analytics

## General Features

* Responsive UI using HTML, CSS, JavaScript
* Secure database connectivity using PHP and MySQL
* Image upload support
* Session-based authentication

---

# Technologies Used

| Technology | Purpose                   |
| ---------- | ------------------------- |
| PHP        | Backend Development       |
| MySQL      | Database Management       |
| HTML5      | Structure of Web Pages    |
| CSS3       | Styling                   |
| JavaScript | Client-side Functionality |
| Bootstrap  | Responsive Design         |
| XAMPP/WAMP | Local Server Environment  |

---

# Project Structure

rescue_app/
│
├── actions/
│   ├── submit_report.php
│   └── update_status.php
│
├── admin/
│   ├── dashboard.php
│   └── login.php
│
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── images/
│   │   ├── dog_hero.png
│   │   └── impact_map.png
│   └── js/
│       └── script.js
│
├── includes/
│   ├── db.php
│   ├── header.php
│   └── footer.php
│
├── ngo/
│   ├── dashboard.php
│   ├── login.php
│   ├── logout.php
│   └── register.php
│
├── user/
│   ├── dashboard.php
│   ├── login.php
│   ├── logout.php
│   └── register.php
│
├── uploads/
│   └── Uploaded animal images
│
├── db.php
├── db_test.php
├── index.php
├── ngo_login.php
├── ngo_register.php
├── report.php
├── style.css
├── test.php
├── user_login.php
├── user_register.php
└── view_reports.php

---

# Installation Steps

## 1. Install XAMPP/WAMP

Download and install:

* XAMPP or
* WAMP Server

## 2. Extract the Project

Place the project folder inside:

htdocs/

for XAMPP.

## 3. Start Apache and MySQL

Open XAMPP Control Panel and start:

* Apache
* MySQL

## 4. Create Database

Open phpMyAdmin and create a database:

animal_rescue

## 5. Import Database

Import the SQL file into phpMyAdmin.

## 6. Configure Database Connection

Update database credentials inside:

includes/db.php

Example:

$conn = mysqli_connect("localhost", "root", "", "animal_rescue");

## 7. Run the Project

Open browser and run:

http://localhost/rescue_app/
---

# Modules Explanation

## Home Page

Displays application overview and navigation links.

## Report Module

Allows users to submit reports of injured or stray animals.

## Dashboard

Separate dashboards are available for users, NGOs, and admin.

## Uploads Module

Stores uploaded animal images securely.

---

# Future Enhancements

* Real-time rescue tracking
* GPS integration
* Email and SMS notifications
* AI-based animal detection
* Online donation system
* Emergency contact support

---

# Advantages

* Easy rescue request management
* Faster communication between users and NGOs
* Centralized database system
* User-friendly interface
* Improves animal welfare awareness

---

# Conclusion

The Animal Rescue App provides an efficient digital solution for reporting and managing animal rescue operations. The system improves coordination between users and NGOs while promoting faster rescue actions and better animal care.

---

# Author

Developed as a PHP Mini Project for academic purposes.
