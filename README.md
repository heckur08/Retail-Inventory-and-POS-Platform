# Inventory Management System with POS

A web-based **Inventory Management System with Point of Sale (POS)** built using **Laravel**.  
This system helps businesses manage products, stock, sales, purchases, customers, employees, and expenses in one place.

---

## Features
- Product, Category & Brand Management  
- POS (Point of Sale) with real-time stock updates  
- Customer & Employee Management  
- Attendance & Expense Tracking  
- Sales Reports & Order History  
- Secure Authentication & Role Management  
- API Endpoints for integration with external services  

---

## Tech Stack
**Backend:** Laravel (PHP), Eloquent ORM, PHPUnit  
**Frontend:** Blade, JavaScript, jQuery, Bootstrap  
**Database:** MySQL / MariaDB  
**Build Tools:** Laravel Mix (Webpack), npm  
**Version Control:** Git  

---

##  Installation
1. Clone the repository  
   ```bash
   git clone https://github.com/heckur08/inventory-management-system-with-pos.git
2. Navigate to project folder
    ```bash
    cd inventory-management-system-with-pos/inventory-management-system-api
3. Install PHP dependencies
    ```bash
    composer install
4. Install JS dependencies
    ```bash
    npm install && npm run dev
5. Setup environment variables
    ```bash
    cp .env.example .env
    php artisan key:generate
6. Run migrations & seeders
    ```bash
    php artisan migrate --seed
7. Start the local server
    ```bash
    php artisan serve

## Usage
- Access the app at `http://127.0.0.1:8000`  
- Login/Register to use POS and inventory features  
- Admin can manage products, employees, and reports  
- Employees can record sales and expenses  

## API Overview
The system includes a REST API with authentication.  
Main modules include:  
- **/api/products** → Manage products  
- **/api/customers** → Manage customers  
- **/api/orders** → Handle orders and POS  
- **/api/employees** → Employee data & attendance  
- **/api/expenses** → Expense tracking  

## License
This project is open-source and available under the [MIT License](LICENSE).
