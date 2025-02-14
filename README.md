# Book Shop Automation

## Overview

Book Shop Automation is a web-based application designed to manage an online bookstore efficiently. It includes features for browsing books, adding them to the cart, managing user accounts, processing orders, and handling administrative tasks.

## Features

- **User Authentication**: Register, login, and logout functionality.
- **Book Management**: Add, edit, and delete books from the store.
- **Cart System**: Add books to the cart and proceed to checkout.
- **Order Management**: Users can place orders and track their purchases.
- **Admin Dashboard**: Manage users, orders, and inventory.
- **Responsive Design**: Works well on different screen sizes.
- **Secure Transactions**: Basic security implementations to prevent unauthorized access.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP, MySQL
- **Styling**: CSS (admin\_style.css, style.css)
- **Database**: MySQL (shop\_db.sql)

## Installation & Setup

### Prerequisites

- XAMPP or any local server with PHP and MySQL support
- Web browser
- Code editor (VS Code, Sublime, etc.)


## Folder Structure

```
📂 book-shop-automation
├── 📂 admin
│   ├── admin_contacts.php
│   ├── admin_header.php
│   ├── admin_orders.php
│   ├── admin_page.php
│   ├── admin_products.php
│   ├── admin_users.php
├── 📂 assets
│   ├── admin_style.css
│   ├── style.css
├── 📂 database
│   ├── shop_db.sql
├── 📂 includes
│   ├── config.php
│   ├── footer.php
│   ├── header.php
├── 📂 public
│   ├── about.php
│   ├── add_to_cart.php
│   ├── cart.php
│   ├── checkout.php
│   ├── contact.php
│   ├── home.php
│   ├── login.php
│   ├── logout.php
│   ├── orders.php
│   ├── register.php
│   ├── search_page.php
│   ├── shop.php
```

## JavaScript Functionality

- Toggles user box and navbar visibility when clicking on buttons.
- Changes the header appearance on scroll.
- Closes product update forms and redirects to admin products page.

## Future Improvements

- Implement secure user authentication using hashed passwords.
- Add payment gateway integration.
- Improve UI/UX with better design elements.
- Optimize the database for better performance.
