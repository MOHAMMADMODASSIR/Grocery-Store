# Grocery-Store
Grocery Store Project using Flask
Grocery Store

This project is a web-based grocery store application developed using Flask, a lightweight web framework for Python. The application allows users to browse through a selection of grocery items, add them to their cart, and place orders.

Features
User Authentication: Users can create accounts, log in, and log out. Passwords are securely stored using hashing techniques.

Product Catalog: A comprehensive list of grocery items is available for users to browse. Each product displays its name, price, and a brief description.

Shopping Cart: Users can add items to their shopping cart. The cart keeps track of the selected items, their quantities, and the total cost.

Order Placement: Once users have added items to their cart, they can proceed to the checkout to place their orders. The application collects shipping information and displays an order summary before confirmation.

Order History: Users can view their order history, including details such as order date, items purchased, quantities, and total cost.

Admin Panel: Admin users have special privileges. They can manage the product catalog by adding, editing, or removing items. Admins can also view and process orders placed by regular users.

Installation
Clone this repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/grocery-store-flask.git
Navigate to the project directory:

bash
Copy code
cd grocery-store-flask
Create a virtual environment to isolate project dependencies:

bash
Copy code
python -m venv venv
Activate the virtual environment:

Windows:

bash
Copy code
venv\Scripts\activate
Linux and macOS:

bash
Copy code
source venv/bin/activate
Install the required dependencies from the requirements.txt file:

bash
Copy code
pip install -r requirements.txt
Set up the database by running the following commands:

bash
Copy code
flask db init
flask db migrate -m "Initial migration"
flask db upgrade
Run the Flask application:

bash
Copy code
flask run
Access the application by opening a web browser and navigating to http://localhost:5000.

Configuration
You can configure the application by editing the config.py file. Here are some configurable options:

SECRET_KEY: A secret key used for encrypting session data.
SQLALCHEMY_DATABASE_URI: The URI for connecting to the database.
MAIL_SERVER, MAIL_PORT, MAIL_USE_TLS, MAIL_USE_SSL, MAIL_USERNAME, MAIL_PASSWORD: Configuration for sending email notifications.
Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and test thoroughly.
Commit your changes with descriptive commit messages.
Push your branch to your forked repository.
Create a pull request detailing your changes.
License
This project is licensed under the MIT License.

Feel free to reach out to us via email at contact@example.com for any questions or feedback! We hope you enjoy using our Grocery Store application built with Flask.
