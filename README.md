
## 🛒 Groceville

Welcome to Online Web Application. Groceville is an online grocery shopping web application, similar to BigBasket, but currently in the development phase.

## 📋 Table of Contents
- [About](#about)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dependencies](#dependencies)
- [Getting Started](#getting-started)
- [Working with Flask, HTML, and CSS](#working-with-flask-html-and-css)
- [Usage](#usage)
- [Database](#database)
- [Contributing](#contributing)
- [License](#license)

## 🏪 About

Groceville is an online grocery shopping web application, similar to BigBasket, but currently in the development phase. It provides a user-friendly interface for customers to browse and purchase a wide variety of grocery items from the comfort of their homes.

## ✨ Features

### 👤 User Features
- 📝 User registration and login
- 🛍️ Browse products by categories
- 🔍 Search for specific items
- 🛒 Add items to cart
- 💳 Place orders
- 📦 Track order status

### 👨‍💼 Admin Features
- 📊 Dashboard for managing products and orders
- ➕ Add new products
- 🗑️ Remove existing products
- ✅ Confirm or reject orders
- 📈 View sales statistics

### 🏷️ Product Categories
- 🥕 Vegetables
- 🍎 Fruits
- 🥛 Dairy Products
- 💄 Cosmetics
- 🥤 Beverages
- ...and more!

## 🛠️ Technologies Used

- Frontend:
  - HTML5
  - CSS3
  - JavaScript

- Backend:
  - Python
  - Flask

- Database:
  - SQLite3

## 📚 Dependencies

- [Python](https://www.python.org/) (3.7+)
- [Flask](https://flask.palletsprojects.com/)
- [SQLite](https://www.sqlite.org/)
- [Requests](https://docs.python-requests.org/)

## 🚀 Getting Started

1. Clone the repository: `git clone https://github.com/yourusername/groceville.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Set up the database: `python setup_database.py`
4. Run the application: `python app.py`
5. Open your web browser and navigate to `http://localhost:5000`

## 🖥️ Working with Flask, HTML, and CSS

### Flask Application Structure

1. The main application logic is in `app.py`. This file contains route definitions and view functions.

2. HTML templates are stored in the `templates/` directory. Flask uses the Jinja2 templating engine.

3. Static files (CSS, JavaScript, images) are stored in the `static/` directory.

## 💻 Usage

1. Register as a new user or log in if you already have an account.
2. Browse the available products by category or use the search function.
3. Add desired items to your cart.
4. Proceed to checkout and place your order.
5. Admin users can log in to the admin panel to manage products and orders.

## 🗄️ Database

Groceville uses SQLite3 for data storage. The database includes tables for:

- User accounts
- Product details
- Order information
- ...and more

## 🤝 Contributing

We welcome contributions to Groceville! Please follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b feature-name`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
