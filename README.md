# 📦 Inventory Management System (Laravel 10 + MySQL)

A complete Inventory Management System built using **Laravel 10**, **MySQL** and **Blade/Tailwind CSS**.  
This system includes modules for product management, suppliers, customers, purchases, sales and a built-in POS (Point of Sale) workflow.

This is my improved and customized version of the open-source project by Fajar Ghifar, with enhanced documentation, usability updates and code understanding.

---

## 🚀 Features

### 🛍️ Product & Inventory Management
- Add, update, delete products  
- Track stock quantity in real time  
- Category management  
- Image upload support  
- Automatic stock updates after sales/purchases  

### 🧾 Purchase & Supplier Management
- Create and manage purchase orders  
- Supplier module with CRUD operations  
- Pending → Approved purchase workflow  
- Auto-update stock after approval  

### 💰 Point of Sale (POS)
- Simple and fast POS interface  
- Add items to cart  
- Adjust quantity  
- Generate invoice  
- Reduce stock automatically after checkout  

### 👥 Customer Management
- Add and manage customer records  
- View customer purchase history  

### 📊 Dashboard & Reports
- Sales summary  
- Purchase summary  
- Stock overview  
- Low stock alerts (optional to add)  

### 🔐 Authentication & Security
- User login & logout  
- Role-based access (Admin/Staff)  
- Backend validation & secure routes  

---

## 🛠 Tech Stack

**Backend:** Laravel 10, PHP 8+  
**Frontend:** Blade Templates, Tailwind CSS  
**Database:** MySQL  
**Auth:** Laravel Breeze / Sanctum (based on setup)  
**Server:** Apache / Nginx  
**Tools:** Composer, NPM, Vite  

---

## 📁 Project Structure

app/
Http/
Controllers/
Middleware/
Models/
database/
migrations/
seeders/
resources/
views/
css/
routes/
web.php
public/

## 🔧 Installation & Setup

1️⃣ Clone the repository

2️⃣ Install PHP dependencies
composer install

3️⃣ Copy environment file
cp .env.example .env

4️⃣ Update database credentials in .env
DB_DATABASE=inventory_app
DB_USERNAME=root
DB_PASSWORD=

5️⃣ Generate application key
php artisan key:generate

6️⃣ Run migrations & seeders
php artisan migrate --seed

7️⃣ Storage link (for images)
php artisan storage:link

8️⃣ Install frontend dependencies & build assets
npm install
npm run dev

9️⃣ Start the development server
php artisan serve

Your app will run at:
http://localhost:8000


🔑 Default Login (if seeded)
Admin Login

Email: admin@example.com
Password: password

🧪 Improvements I Added
-> Updated UI styling
-> Added improvements to validation
-> Cleaned and documented code
-> Added comments and restructuring for learning


📜 License
This project is open-source under the MIT License.








































