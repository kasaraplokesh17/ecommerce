# 🛒 E-Commerce Website (PHP + MySQL)

A simple and functional **E-Commerce Web Application** built using **PHP, MySQL, HTML, CSS**.
This project allows users to browse products, add them to cart, and manage basic shopping operations.

---

## 🚀 Features

* 🔐 User Authentication (Login & Register)
* 🛍️ Product Listing
* 🛒 Add to Cart functionality
* 🧾 Cart Management
* 🖼️ Product Images display
* 📦 Database-driven content
* 🔓 Session-based user handling

---

## 🏗️ Tech Stack

* **Frontend:** HTML, CSS
* **Backend:** PHP
* **Database:** MySQL
* **Server:** Apache (XAMPP / WAMP)

---

## 📂 Project Structure

```
ecommerce/
│── includes/
│   └── db.php          # Database connection
│
│── pages/
│   ├── login.php       # User login
│   ├── register.php    # User registration
│   ├── cart.php        # Cart functionality
│
│── css/
│   └── style.css       # Styling
│
│── images/             # Product images
│
│── index.php           # Homepage (Product listing)
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/Balamaloth/ecommerce.git
```

2. **Move project to server folder**

* XAMPP → `htdocs`
* WAMP → `www`

3. **Start Apache & MySQL**

4. **Create Database**

* Open phpMyAdmin
* Create database: `ecommerce`

5. **Import tables**

* Create a `products` table manually or import SQL file

Example structure:

```sql
CREATE TABLE products (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255),
    price DECIMAL(10,2),
    description TEXT,
    image VARCHAR(255)
);
```

6. **Update DB connection**
   Edit:

```
includes/db.php
```

---

## ▶️ Run the Project

Open browser:

```
http://localhost/ecommerce/
```

---

## 📸 Screenshots (Optional)

* Homepage with products
* Cart page
* Login/Register page

---

## 🔮 Future Improvements

* ✅ Payment Gateway Integration
* ✅ Admin Panel (Add/Edit/Delete products)
* ✅ Order History
* ✅ Search & Filters
* ✅ User Profile


* 🛠️ Improve it

---
