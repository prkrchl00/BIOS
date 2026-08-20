# BIVOS – Beverage Inventory and Ordering System

## 📌 About the Project

**BIVOS (Beverage Inventory and Ordering System)** is a web-based beverage inventory and ordering system developed for **Betting Sari-Sari Store**. The system is designed to streamline product and inventory management, customer ordering, transactions, deliveries, and sales monitoring through a centralized platform.

BIVOS provides dedicated portals for **Admin/Owner, Customer, and Delivery Staff**, with features tailored to each user's role and responsibilities.

The system also provides automated **product alerts** to help the administrator monitor products with **low stock levels** and products that are **approaching their expiration date**.

---

## ✨ Features

### 🔐 Admin/Owner Portal

The Admin/Owner portal provides tools for managing the store's products, orders, transactions, deliveries, and users.

* **Dashboard**

  * Overview of orders and sales
  * Pending, cancelled, delivered, and completed orders
  * Registered user count
  * Monthly sales chart
  * Weekly sales chart
  * Top-selling products
  * Delivery staff transaction monitoring

* **Walk-In Transactions**

  * Record and manage walk-in customer transactions
  * Process in-store purchases

* **Order Management**

  * View and manage customer orders
  * Monitor order status
  * Process delivery orders
  * Manage cancelled and completed orders

* **Product Management**

  * Add, edit, and manage beverage products
  * Manage product information and pricing
  * Monitor product availability

* **Product Alerts**

  * **Low Stock Alerts** – identifies products that are running low on inventory
  * **Near-Expiration Alerts** – identifies products approaching their expiration date
  * Helps the administrator take action before products become unavailable or expire

* **Issue Reports**

  * View and manage reported issues
  * Monitor concerns related to orders and transactions

* **Transaction Management**

  * View transaction records
  * Monitor completed transactions

* **Reports**

  * Generate and view sales reports
  * Monitor inventory and transaction information
  * Analyze sales performance

* **Messages**

  * Manage system messages and communications

* **Delivery Settings**

  * Configure delivery-related settings
  * Manage delivery options and schedules

* **Delivery Staff Management**

  * Manage delivery staff accounts
  * Monitor delivery staff activities and transactions

---

### 🛒 Customer Portal

The Customer portal allows customers to browse products, place orders, and monitor their purchases.

* Customer registration and login
* Customer dashboard
* Browse available beverage products
* Search for products
* Add products to cart
* Place orders
* View order details
* View order status
* Monitor delivery information
* View notifications
* View current purchases
* View order history
* Manage customer account
* View completed and cancelled orders

---

### 🚚 Delivery Staff Portal

The Delivery Staff portal is designed for managing and completing assigned deliveries.

* Delivery staff login
* Delivery staff dashboard
* View assigned orders
* View customer delivery information
* View order details
* Manage assigned deliveries
* Update delivery/order status
* Monitor pending deliveries
* View completed deliveries
* View delivery transaction records

---

## 🛠️ Technologies Used

* **HTML** – Web page structure
* **CSS** – User interface styling
* **JavaScript** – Interactive functionality
* **PHP** – Server-side development and system logic
* **MySQL** – Database management
* **Bootstrap** – Responsive interface and UI components

---

## 👥 User Roles

 User Role          | Main Responsibilities                                                                            
 **Admin/Owner**    | Manage products, inventory, orders, transactions, reports, users, deliveries, and product alerts 
 **Customer**       | Browse products, place orders, view purchases, and monitor order/delivery status                 
 **Delivery Staff** | Manage assigned deliveries and update delivery status                                            

---

## 📂 System Structure

```text
BIVOS
│
├── Admin/Owner Portal
│   ├── Dashboard
│   ├── Walk-In Transactions
│   ├── Orders
│   ├── Manage Products
│   ├── Product Alerts
│   │   ├── Low Stock
│   │   └── Near Expiration
│   ├── Issue Reports
│   ├── Transactions
│   ├── Reports
│   ├── Messages
│   ├── Delivery Settings
│   └── Delivery Staff
│
├── Customer Portal
│   ├── Dashboard
│   ├── Products
│   ├── Notifications
│   ├── My Purchases
│   ├── Order History
│   └── My Account
│
└── Delivery Staff Portal
    ├── Dashboard
    ├── Assigned Orders
    ├── Delivery Information
    ├── Delivery Status
    └── Completed Deliveries

## 🚀 Installation

1. Install a local development environment such as **XAMPP**.
2. Clone or download this repository.
3. Place the project folder inside the XAMPP `htdocs` directory.
4. Start **Apache** and **MySQL** using the XAMPP Control Panel.
5. Create the BIVOS database in **phpMyAdmin**.
6. Import the provided `.sql` database file.
7. Configure the database connection in the project's PHP configuration file.
8. Open the system in your browser:
