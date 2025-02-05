🌸 Perfume Store Website
A fully functional perfume e-commerce website where users can browse perfumes, filter products based on brand or price, add items to the cart, and log in to their accounts.

🚀 Features
🔐 User Authentication: Users can register and log in.
🛍️ Product Display: View perfumes with details.
🎯 Product Filtering: Filter perfumes by brand and price.
🛒 Shopping Cart: Add products to the cart.
🛠️ Technologies Used
Frontend: HTML, CSS, JavaScript
Backend: PHP
Database: MySQL

Here's a clean and ready-to-copy version of the installation steps for your README.md file:

---

⚙️ Installation  

### Step 1: Clone the Repository  
1. Open your terminal or Git Bash.  
2. Clone the repository to your local machine:  
   ```bash
   git clone https://github.com/Rrachana14/Perfume-Website.git
   cd Perfume
   ```

### Step 2: Set Up the Environment with XAMPP  
1. Make sure [XAMPP](https://www.apachefriends.org/) is installed and running on your system.  
2. Move the extracted project folder to the XAMPP `htdocs` directory:  
   - Example: `C:\xampp\htdocs\Perfume`

### Step 3: Import the Database  
1. Open **phpMyAdmin** in your browser by navigating to:  
   ```url
   http://localhost/phpmyadmin
   ```
2. Create a new database (`ecommerce`).  
3. Import the SQL file included in the project:  
   - Click on the database name -> Import -> Choose File -> Select the `.sql` file -> Click "Go".

### Step 5: Configure the Database Connection  
1. Open the project folder and locate the database connection file (e.g., `db.php` or `config.php`).  
2. Update the database configuration details:  
   ```php
   $host = 'localhost';
   $username = 'root';
   $password = '';
   $dbname = 'ecommerce';
   ```

### Step 6: Start the Server and Access the Website  
1. Start the **Apache** and **MySQL** modules in the XAMPP Control Panel.  
2. Open your browser and navigate to:  
   ```url
   http://localhost/Perfume
   ```


