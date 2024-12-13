# Online Book Selling Website  

## Overview  
The *Online Book Selling Website* is a fully functional e-commerce platform that enables users to browse, purchase, and manage books online. It is designed to meet the needs of both users and administrators, offering seamless functionality, security, and scalability. Users can explore a wide range of books, add them to their cart, and complete purchases through secure payment methods. Administrators have the tools to manage book inventories, track orders, and oversee user accounts efficiently.  

---

## Features  

### **User Features**  
- **Secure User Authentication:** Users can sign up, log in, and manage their profiles securely.  
- **Book Browsing:** Search, filter, and explore books by category, author, genre, and price.  
- **Shopping Cart:** Add books to the cart, adjust quantities, and review selections.  
- **Checkout Process:** Complete purchases with secure payment options.  
- **Order History:** View and track previous orders.  

### **Admin Features**  
- **Admin Dashboard:** Comprehensive view of user activities, orders, and system status.  
- **Book Management:** Add, update, or remove books from the catalog.  
- **Order Management:** Track and manage customer orders, including payment status and delivery.  
- **User Management:** Monitor and manage registered users.  

### **Additional Features**  
- **Responsive Design:** Optimized for desktops, tablets, and mobile devices.  
- **Secure Payment Integration:** Ensures safe transactions through encrypted protocols.  
- **Real-Time Inventory Updates:** Tracks stock availability dynamically.  

---

## Technology Stack  
- **Frontend:** HTML, CSS, Bootstrap, JavaScript, AJAX  
- **Backend:** PHP  
- **Database:** MySQL  
- **Development Tools:** Visual Studio Code, XAMPP  

---

## Installation Instructions  

### **Clone the Repository:**  
```bash
git clone https://github.com/kazisharfunnabi/onlinebookshop.git
```
### **Navigate to the Project Directory:**
```bash
cd onlinebookshop
```
### **Set Up the Database:**
- Open phpMyAdmin via XAMPP.
- Create a new database, e.g., bookstore.
- Import the SQL file located in the repository (database.sql) into the created database.

### **Configure the Project:**
- Open the project folder in your code editor.
- Update the database configuration in config.php:
```php
$servername = "localhost";  
$username = "root";  
$password = "";  
$dbname = "bookstore";
```  

### **Run the Server:**
- Start Apache and MySQL in XAMPP.
- Visit http://localhost/onlinebookshop/ in your browser to access the website.
---


## Usage Instructions
### **For Users:**
- Sign up for a new account or log in if you already have one.
- Browse the book catalog and add desired books to your shopping cart.
- Proceed to checkout, provide necessary details, and complete the purchase.
- Access your account to track orders or update personal information.
### **For Admins:**
- Log in using admin credentials.
- Use the admin dashboard to:
- Add or edit book listings.
- Monitor and manage user accounts.
- Track and process customer orders.
---
## Screenshots
- Homepage
- Admin Dashboard
- Shopping Cart
---
## Contribution Guidelines
**Contributions are welcome! If you’d like to contribute:**

**Fork the repository.**
Create a feature branch:
```bash
git checkout -b feature-name
```
**Commit your changes:**
```bash
git commit -m "Description of changes"
```
**Push the branch:**
```bash
git push origin feature-name
```
#### Create a pull request to the main branch.
---

## Acknowledgments
- **Frameworks and Tools:** Bootstrap, jQuery
- **Development Tools:** XAMPP, phpMyAdmin
- **Learning Resources:**
    - W3Schools
    - PHP Official Documentation
```vbnet
Copy this into your `README.md` file. This ensures the markdown is properly formatted and displays correctly on GitHub without any issues. Let me know if you need more help!
```
