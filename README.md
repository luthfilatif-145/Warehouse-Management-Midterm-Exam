# Warehouse Management Midterm Exam Project

A web-based warehouse management system with user authentication and an admin panel for managing products. Built with PHP as a midterm project.

## Features

**Authentication & User Management**
- User registration with account activation (`register.php`, `aktivasi.php`)
- Login and logout (`index.php`, `logout.php`)
- Forgot password and reset password flow (`lupa_password.php`, `reset_password.php`)
- User profile page (`profil.php`)

**Admin Panel**
- Admin dashboard (`dashboard.php`)
- Product management: [view, add, edit, delete] products (`kelola_produk.php`, `kelola_produk_input.php`)
- Reusable header and footer components (`inc_header.php`, `inc_footer.php`)

## Tech Stack

- PHP
- [MySQL]
- [HTML / CSS / Bootstrap]
- [XAMPP for local development]

## Project Structure

```
web_gudang/
├── admin/
│   ├── dashboard.php
│   ├── inc_header.php
│   ├── inc_footer.php
│   ├── kelola_produk.php
│   ├── kelola_produk_input.php
│   ├── profil.php
│   ├── lupa_password.php
│   ├── reset_password.php
│   └── logout.php
├── aktivasi.php
├── db_config.php
├── index.php
└── register.php
```

## Installation

1. Clone this repository
```
   git clone https://github.com/luthfilatif-145/Warehouse-Management-Midterm-Exam.git
```
2. Move the `web_gudang` folder into your `htdocs` directory (XAMPP)
3. Create a MySQL database named `[database_name]` and import the SQL file [if available]
4. Edit `db_config.php` and set your own database credentials
5. Start Apache and MySQL, then open `http://localhost/web_gudang`

## Screenshots

(Add screenshots of the login page, dashboard, and product management page here)

## Author

Luthfi Latif - [GitHub](https://github.com/luthfilatif-145)
