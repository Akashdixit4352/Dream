DreamVenue - Event Booking Website
Overview
DreamVenue is a web application designed to facilitate the booking of events at various venues. The project is developed using a combination of HTML, CSS, JavaScript, PHP, XAMPP, and MySQL technologies. This README provides essential information for setting up, running, and contributing to the DreamVenue project.

Features
User Authentication: Users can create accounts, log in, and manage their profiles.
Venue Listings: View a list of available venues for booking events.
Booking System: Users can book venues for specific dates and times.
Admin Panel: Admins have access to manage venues, bookings, and user accounts.
Responsive Design: The website is designed to work seamlessly across various devices.
Prerequisites

To run the DreamVenue project, ensure you have the following installed:
XAMPP: A cross-platform web server solution stack containing Apache, MySQL, PHP, and Perl.
Web Browser: For testing and running the application.
Setup Instructions
Clone the repository:

bash
Copy code
git clone https://github.com/Akashdixit4352/Dream.git
Move the project folder to the XAMPP htdocs directory.

Start XAMPP and ensure both Apache and MySQL servers are running.

Import the Event_Management_System.sql file into your MySQL database. This file contains the necessary tables and sample data.

Open a web browser and navigate to http://localhost/Event_Management_System.

The DreamVenue website should be up and running. You can log in using the sample admin credentials:
Username: admin
Password: admin123

Project Structure
The project structure is organized as follows:

css/: Contains CSS stylesheets.
js/: Houses JavaScript files.
php/: Contains PHP scripts for server-side functionality.
images/: Stores image assets.
admin/: Admin panel files.
includes/: Commonly used PHP files for header, footer, etc.
index.php: The main entry point of the application.
Contributing
If you want to contribute to DreamVenue, follow these steps:

Fork the repository.
Create a new branch: git checkout -b feature/new-feature.
Commit your changes: git commit -m 'Add new feature'.
Push to the branch: git push origin feature/new-feature.
Submit a pull request.

Feel free to explore, modify, and improve DreamVenue! Happy coding!
