🚌 Bus Pass Management System
📌 Overview

Bus Pass Management System is a web-based application that automates the process of applying, renewing, and managing bus passes online. It reduces manual paperwork, saves time, and makes the approval process faster and more transparent for both users and administrators.

✨ Features
👤 User Module

User Registration & Login

Apply for New Bus Pass

Renew Existing Bus Pass

Upload / Enter Required Details

View Application Status (Pending / Approved / Rejected)

View Pass Details

🛠️ Admin Module

Admin Login

View All Applications

Approve / Reject Pass Requests

Manage User Records

Update Pass Information

Maintain Pass History

🧰 Tech Stack

Frontend: HTML, CSS, JavaScript

Backend: PHP

Database: MySQL

Tools: VS Code, XAMPP, Git, GitHub

🗂️ Project Structure
bus-pass-management-system/
│
├── admin/              # Admin panel files
├── css/                # Stylesheets
├── js/                 # JavaScript files
├── images/             # Images
├── includes/           # Database & reusable components
├── index.php           # Home page
└── README.md
🚀 How to Run the Project
✅ Step 1: Clone the Repository
git clone https://github.com/arbasm/bus-pass-management-system.git
✅ Step 2: Move Project to XAMPP

Copy the project folder

Paste it inside:

C:\xampp\htdocs\
✅ Step 3: Start XAMPP

Start Apache

Start MySQL

✅ Step 4: Create Database

Open browser

Go to:

http://localhost/phpmyadmin

Create a new database (example: buspassms)

Import the provided SQL file (if available)

✅ Step 5: Configure Database Connection

Open:

includes/dbconnection.php

Update with your database details:

$host = "localhost";
$username = "root";
$password = "";
$dbname = "buspassms";
✅ Step 6: Run the Project

Open browser and visit:

http://localhost/buspassms

Admin Panel:

http://localhost/buspassms/admin
🔐 Default Admin Login (If Available)
Username: admin
Password: admin123

(Change credentials after first login for security.)

📈 Future Enhancements

Online Payment Integration

Email / SMS Notifications

QR Code Based Pass Verification

User Profile Management

Dashboard Analytics

📄 License

This project is developed for educational purposes.
