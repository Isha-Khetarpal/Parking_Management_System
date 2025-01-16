# Parking Management System

The **Parking Management System** is a web-based application designed to manage parking spaces, vehicles, and user profiles efficiently. The system offers both an **Admin Panel** for managing parking categories, vehicles, and user information, and a **User Panel** for managing vehicle entries, profiles, and parking availability. This project is built using **HTML**, **CSS**, **JavaScript**, **PHP**, and **SQL**.

## Features

### Admin Panel:
- **Manage Parking Categories**: Add, edit, and delete categories for parking spaces.
- **Manage Vehicles**: Add new vehicles, update vehicle details, and view vehicle history.
- **User Management**: View and edit user profiles, manage vehicle registrations, and track parking usage.
- **Report Generation**: Generate reports for parking usage and vehicle entries/exits.
  
### User Panel:
- **User Authentication**: Users can sign up, log in, and reset passwords.
- **Manage Profile**: Users can update their profile and view their parking history.
- **Vehicle Management**: Users can add new vehicles, view vehicle details, and track parking space availability.

### Responsive Design:
- The application is built with a responsive user interface to ensure seamless experience across desktop, tablet, and mobile devices.

## Tech Stack

- **Frontend**:
  - HTML
  - CSS
  - JavaScript
  
- **Backend**:
  - PHP
  
- **Database**:
  - SQL (vpmsdb.sql)

- **Libraries and Tools**:
  - Custom JavaScript for dynamic content and interactivity.
  - PHP for backend functionality and database interactions.
  - SQL database for storing parking and user data.

## Project Files Overview

### Database (SQL):
- **`SQL File/vpmsdb.sql`**: Contains the schema for the parking management database, including tables for parking categories, vehicles, users, and more.

### Admin Panel Files:
- **`admin/add-category.php`**: PHP file for adding new parking categories.
- **`admin/add-vehicle.php`**: PHP file for adding new vehicles to the system.
- **`admin/dashboard.php`**: The main admin dashboard for managing the system.
- **`admin/edit-category.php`**: PHP file for editing parking categories.
- **`admin/admin-profile.php`**: Admin profile management.
- **`admin/assets/css/`**: CSS files for styling the admin panel interface, including custom styles and library styles.
  - `style.css`: The primary CSS file for admin styles.
  - `lib/chosen/`: Folder containing styles for dropdown selections and custom inputs.
- **`admin/assets/js/`**: JavaScript files for dynamic functionality and dashboard interactivity.
  - Includes charting, data tables, and map integration.
- **`admin/images/`**: Folder containing images used for the admin panel (e.g., profile pictures, logos, avatars).

### User Panel Files:
- **`users/login.php`**: Login page for users to access the system.
- **`users/signup.php`**: Signup page for new users to register.
- **`users/profile.php`**: Profile management page for users.
- **`users/dashboard.php`**: User dashboard displaying vehicle details and parking information.
- **`users/includes/`**: Folder containing common PHP files for database connections, header, footer, and sidebar.

### Miscellaneous Files:
- **`assets/`**: Contains images and icons used across the project.
- **`css/styles.css`**: Global styles for the user-facing pages.
- **`js/scripts.js`**: JavaScript file for handling user-facing functionality.

## Installation

To run this project locally, follow the steps below:

### Breakdown of Sections:

1. **Project Description**: The purpose and overview of the Parking Management System.
2. **Features**: A breakdown of what the admin and user can do within the system.
3. **Tech Stack**: Specifies the technologies and tools used.
4. **Project Files Overview**: Describes important files and their locations.
5. **Installation**: Step-by-step instructions for setting up the project locally.
6. **Usage**: Instructions on how the admin and users will interact with the system.
7. **License**: Information about the project’s open-source license.
8. **Acknowledgements**: Credits for libraries and contributors.

### Clone the repository:
```bash
git clone https://github.com/Isha-Khetarpal/Parking_Management_System.git
