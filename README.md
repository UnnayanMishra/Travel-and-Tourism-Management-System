# Travel Tourism Management System

## Project Overview

The **Travel Tourism Management System** is a Java-based application designed to manage various aspects of a tourism business. It allows administrators to manage customer information, tour packages, bookings, and payments. The system is built to provide a seamless experience for both the business and the customers, enabling efficient booking and tour management.

## Features

- User Registration/Login: Secure login for administrators and customers.
- Customer Management: Add, update, delete customer information.
- Tour Packages: Manage various tour packages with details like destination, price, and itinerary.
- Booking Management Customers can book available tour packages.
- Payment System: Process payments and generate invoices for bookings.
- Search and Filter Search for packages by destination, duration, or price.
- Admin Panel: Admins can manage the system (add/remove packages, view bookings, etc.).
- Report Generation: Generate reports of bookings, payments, and package popularity.

## Technologies Used

- Java: Core programming language used for development.
- JavaFX: For building the GUI (Graphical User Interface).
- JDBC: To handle database connectivity.
- MySQL As the backend database for storing customer, package, and booking information.
- Maven For dependency management and project build.
- JasperReports Used for generating reports (optional).
- JUnit: For testing purposes.

## Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/TravelTourismManagement.git
   
2. Database Setup:
  Install MySQL and create a database for the application.
  Import the database schema provided in the /db folder (tourism.sql).

3.Configure Database Connection:
  In the src/config/DBConnection.java file, update the database connection credentials:
  String url = "jdbc:mysql://localhost:3306/your-database";
  String username = "your-username";
  String password = "your-password";

4.Run the Application:
  Use your preferred IDE (like IntelliJ IDEA or Eclipse) to open the project.
  Build the project using Maven:
  mvn clean install
  Run the Main.java file to start the application.

#Usage
1 . Admin Login:

- Use the default admin credentials to log in (these can be changed in the database).
- Username: admin
- Password: admin123
- Customer Registration/Login:

2. New users can register by providing their details.
- Existing users can log in to view and manage their bookings.
- Managing Packages:

3. Admin can add new tour packages by specifying the destination, price, duration, and description.
- Admin can also edit or delete existing packages.
- Booking a Package:

4. Customers can search for packages by destination or price range.
- Once a package is selected, the customer can book it and proceed to payment.

5. Generating Reports:
-Admin can generate booking and payment reports to keep track of the business operations.

# Future Enhancements
- Add email notification for bookings and payments.
- Add dynamic pricing based on season and availability.
- Integrate payment gateway for online payments.
- Add customer reviews and ratings for packages.



