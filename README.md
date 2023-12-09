# GasBookingSystem
The Online Gas Booking System is a web-based application designed to streamline the process of gas booking. Built with HTML, CSS, PHP, and JavaScript, this system includes features for both administrators and users. It utilizes the EmailJS service for email notifications and ensures secure data management with a connected database.

## Getting Started

Follow these steps to set up and run the Online Gas Booking System on your local machine.

### Prerequisites

1. **Web Server:** Install a web server (e.g., Apache) to host PHP files.
2. **Database:** Set up a MySQL database and ensure it's running.
3. **EmailJS Account:** Create an account on [EmailJS](https://www.emailjs.com/) for email notifications.

### Installation

1. **Clone the Repository:**
   > git clone https://github.com/YOUR_USERNAME/online-gas-booking-system.git
2. **Navigate to the Project Directory:**
   >cd online-gas-booking-system
3. **Import Database Schema:**
   >mysql -u your_username -p your_database_name < database.sql
4. **Update Configuration:**
   * Edit config.php with your database credentials and EmailJS API key.
## Usage
### User Dashboard:
* Users can log in, book gas, view booking status, and update profiles.
* Access the User Dashboard at http://localhost/online-gas-booking-system/user-dashboard.php.
### Admin Dashboard:
* Administrators can log in, view/approve bookings, manage users, and view statistics.
* Access the Admin Dashboard at http://localhost/online-gas-booking-system/admin-dashboard.php.
### Email Notifications:
* The EmailJS service sends notifications for booking approval and updates.
##  Features
### User Management:

* Registration and profile management.
### Booking System:

* Users can book gas; admins can approve/reject bookings.
### Dashboard:

* Separate dashboards for users and admins.
## Acknowledgments
The Online Gas Booking System is designed to simplify gas booking, providing an intuitive interface for users and efficient management tools for administrators. The project is built with HTML, CSS, PHP, and JavaScript.

## Contact
For inquiries or assistance, contact -Poornasri:

* Email: poornaperiyasamy@gmail.com

