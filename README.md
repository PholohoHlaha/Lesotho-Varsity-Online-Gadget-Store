Lesotho Varsity Online Gadget Store
Overview

Lesotho-Varsity-Online-Gadget-Store is an online store developed using PHP, LESS, JavaScript. It is designed with a minimalist approach to Human-Computer Interaction (HCI), ensuring a user-friendly and efficient shopping experience. The project allows users to view and purchase gadgets, with admin capabilities to manage stock and track purchases.
Features
User Functionality

    Browse and search for gadgets.
    Select the delivery location.
    Track purchases and order history.

Admin Functionality

    Add new stock (gadgets) to the system.
    Update existing stock information.
    Manage and track inventory based on purchases.
    Admin login:
        Username: admin@admin.com
        Password: password

Design

    Minimalist concept for intuitive user interaction.
    Web-based interface, accessible on any OS.

Installation
Prerequisites

    XAMPP or any similar web server software that includes PHP and MySQL.
    Basic understanding of how to manage MySQL databases using phpMyAdmin or the command line.

Step-by-Step Installation
1. Download and Extract the Project Files

Download the project files from the GitHub repository and extract them to your local machine.
2. Set Up the Web Server
On Linux

    Install XAMPP:
        Download XAMPP from Apache Friends.
        Run the installer and follow the instructions.

    Move Project Files to htdocs:

    sh

sudo mv path_to_extracted_files /opt/lampp/htdocs/Lesotho-Varsity-Online-Gadget-Store

Start XAMPP:

sh

    sudo /opt/lampp/lampp start

On Windows

    Install XAMPP:
        Download XAMPP from Apache Friends.
        Run the installer and follow the instructions.

    Move Project Files to htdocs:
        Copy the extracted files to C:\xampp\htdocs\Lesotho-Varsity-Online-Gadget-Store.

    Start XAMPP:
        Open the XAMPP Control Panel.
        Start Apache and MySQL.

On macOS

    Install XAMPP:
        Download XAMPP from Apache Friends.
        Run the installer and follow the instructions.

    Move Project Files to htdocs:

    sh

    sudo mv path_to_extracted_files /Applications/XAMPP/htdocs/Lesotho-Varsity-Online-Gadget-Store

    Start XAMPP:
        Open the XAMPP Control Panel and start the services.

3. Set Up the Database

    Open phpMyAdmin:
        Go to http://localhost/phpmyadmin.

    Create a New Database:
        Name it ecomm.

    Import the Database:
        Select the ecomm database.
        Click on the Import tab.
        Choose the ecomm.sql file from the extracted project files.
        Click Go.

4. Configure the Project

    Update Database Configuration:
        Open the project directory.
        Locate the configuration file (usually config.php or similar).
        Update the database credentials to match your MySQL setup.

php

// Example configuration
define('DB_SERVER', 'localhost');
define('DB_USERNAME', 'root');
define('DB_PASSWORD', '');
define('DB_DATABASE', 'ecomm');

5. Access the Project

    Open a web browser and go to http://localhost/Lesotho-Varsity-Online-Gadget-Store.

Customization

    User Interface: Modify the LESS and JavaScript files to customize the look and feel of the store.
    Functionality: Update the PHP files to add or modify features according to your requirements.

Admin Functionality

    Add New Stock:
        Log in to the admin panel.
        Navigate to the stock management section.
        Add new gadgets with details such as name, description, price, and stock quantity.

    Update Stock Information:
        Select an existing gadget.
        Update the required information.
        Save the changes.

    Manage Inventory:
        Track stock levels based on user purchases.
        Update stock quantities as needed.

Period

This project follows all software design principles, it was developed within a period of a semester, 3 months.
Contact

For any inquiries or questions, please contact pholohohlaha@gmail.com.
