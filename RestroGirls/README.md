# RestroGirls

A Simple Demo Restaurant Management System in PHP.

---

## Tech Stack
- PHP 7.x
- MySQL / MariaDB
- Apache (via XAMPP)
- Materialize CSS
- jQuery + AJAX

---

## Setup Instructions

### Prerequisites
- XAMPP (Apache + MySQL) installed and running

### Steps

1. **Copy project to web root**
   - Place the `RestroGirls/` folder inside your XAMPP `htdocs/` directory.
   - Path: `C:/xampp/htdocs/RestroGirls/` (Windows) or `/opt/lampp/htdocs/RestroGirls/` (Linux)

2. **Import database**
   - Open phpMyAdmin: `http://localhost/phpmyadmin`
   - Create a new database named `mishtidb`
   - Import `mishtidb.sql` from the project root

3. **Configure DB connection** (if needed)
   - Edit `backends/config.php`
   - Default: host=`localhost`, user=`root`, password=`""`, db=`mishtidb`

4. **Run the project**
   - Frontend: `http://localhost/RestroGirls/`
   - Admin panel: `http://localhost/RestroGirls/admin/`

---

## Default Credentials

| Role  | Email             | Password |
|-------|-------------------|----------|
| Admin | admin@gmail.com   | 12345    |
| User  | mishti@gmail.com  | 12345    |

---

## Features
- User registration & login (AJAX-based)
- Browse food categories and items
- Place food orders (login required)
- Admin dashboard: manage categories, foods, view orders
