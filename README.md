# Bike Showroom Management System

The **Bike Showroom Management System** is a PHP-based web application designed to streamline the operations of a bike showroom. It includes features for both administrators and customers, providing a seamless experience for managing bike inventory, components, and bookings.

## Features

### Admin Features

- Manage bike inventory (Add, remove, update bikes).
- Manage bike components.
- View and manage customer bookings.
- Admin profile management.

### Customer Features

- View available bikes and their details.
- Book bikes for purchase or test rides.
- View and manage personal bookings.
- Customer profile management.

## Project Structure

### Main Files

- **index.php**: Homepage of the application.
- **login.php**: User login page.
- **signup.php**: User registration page.
- **logout.php**: User logout functionality.
- **welcome_admin.php**: Admin dashboard.
- **welcome_cust.php**: Customer dashboard.
- **add_removebikes.php**: Add or remove bikes (Admin).
- **add_removecomp.php**: Add or remove bike components (Admin).
- **cust_profile.php**: Customer profile page.
- **admin_profile.php**: Admin profile page.
- **cust_bookings.php**: Manage customer bookings.
- **view_bookbike.php**: Book a bike (Customer).
- **yourbookings.php**: View your bookings (Customer).
- **view_comp.php**: View available components.

### Partials

- **_dbconnect.php**: Handles database connections.
- **_nav.php**: Navigation bar for general users.
- **_navcust.php**: Navigation bar for customers.

### Database

- **queries.sql**: Contains SQL queries to set up and populate the database.

### Images

- Various bike images stored in the `images/` folder (e.g., `bajaj.jpg`, `ducati.jpeg`, etc.).

## Installation and Setup

1. **Install Prerequisites**  
   - Install a local server like [XAMPP](https://www.apachefriends.org/) or [WAMP](https://www.wampserver.com/).  
   - Ensure PHP and MySQL are installed and running.

2. **Clone or Download the Project**  
   - Download the project and extract it into the `htdocs` folder of your local server.

3. **Setup Database**  
   - Open MySQL or phpMyAdmin.  
   - Create a new database (e.g., `bike_showroom`).  
   - Import the `queries.sql` file to set up the necessary tables and data.

4. **Run the Application**  
   - Start your local server.  
   - Open your browser and navigate to `http://localhost/Bike_Showroom`.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: PHP  
- **Database**: MySQL  

## Screenshots

- Sample bike images and dashboard layouts are included in the `images/` folder.

## Contribution

Feel free to contribute to this project by forking the repository and submitting pull requests.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.
