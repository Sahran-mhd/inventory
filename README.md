# 📦 Computer Science Department Inventory Management System

This project is a web-based **Inventory Management System** designed for the Computer Science Department to manage assets efficiently. It helps track, update, and maintain departmental inventory records in a user-friendly way.

## 🔧 Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL

## ✅ Features

- 📋 **Add and Manage Items**  
  Add new inventory items with details like item name, category, quantity, location, and condition.

- 🔍 **Search and Filter**  
  Quickly find items using keyword search or by category and status filters.

- 🔄 **Update & Delete**  
  Modify existing item details or remove outdated entries.

- 👤 **User Authentication (Optional)**  
  Secure login system to manage user roles (admin, staff).

- 📊 **Reports (Optional)**  
  Generate basic inventory reports for audits or departmental use.

## 📁 Folder Structure (Example)

├── HomePage/ # Landing page of the system
├── Multimedia/ # Manage multimedia inventory
├── admin/ # Admin dashboard and controls
├── config/ # Database connection and configuration files
├── css/ # Stylesheets for frontend UI
├── furniture/ # Manage furniture inventory
├── header/ # Common header/navigation code
├── image/ # UI images
├── lab/ # Manage lab equipment
├── login/ # Login system
├── office/ # Office-related inventory
├── img5.jpg # Image asset
└── project_1.sql # MySQL database dump

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
2.Set Up the Database
  Import project_1.sql into your MySQL server using phpMyAdmin or any tool.

3.Configure Database Connection
  Edit config/your-db-file.php with your MySQL credentials.

4.Run Locally
  Place the project in your XAMPP/WAMP htdocs folder.
  Start Apache and MySQL.
  Open http://localhost/your-project-folder/HomePage/ in a browser.
