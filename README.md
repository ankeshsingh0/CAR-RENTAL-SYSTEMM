# CAR-RENTAL-SYSTEMM

Car Rental System is a Java-based desktop application designed to provide a seamless vehicle rental experience. This project features a graphical user interface for customers and admins, built using Java Swing, with PostgreSQL as the database hosted on AWS. The system supports vehicle booking, user management, and administrative controls.




Features                                                                                     Customer Features                                                                            Browse Vehicles: View available vehicles and filter by type or availability date.     
    Book Vehicles: Easily book vehicles and specify rental dates.
    View Bookings: Manage active, completed, or canceled bookings.
    Notifications: Receive reminders about booking deadlines.
    Invoices: Generate and download PDF invoices for completed bookings.
    My Account: Update account details, such as name, phone number, and password.

    Admin Features
    Manage Vehicles: Add, edit, or remove vehicles in the fleet.
    Manage Bookings: Oversee all bookings, including the ability to cancel them.
    Generate Reports: View detailed analytics, such as total revenue, active bookings, and
    customer statistics.


FOLDER STRUCTURE



CS342-Car-Rental/
├── .idea/                 # IntelliJ IDEA configuration files
├── report/                # Documentation files for the project
├── src/
│   ├── main/java/org/example/
│       ├── classes/       # Core business entities (e.g., User, Booking, Vehicle)
│       ├── common/        # Shared utilities (e.g., Validation, DatabaseHandler)
│       ├── controllers/   # Controllers for handling database operations
│       ├── res/           # Resources (images/icons for GUI) and schema for database in SQL
│       ├── view/          # Main GUI components (Admin and Customer GUIs)
│       ├── views/         # Additional GUI components for customer functionality
│       └── Main.java      # Main entry point of the application
├── .gitignore             # Git ignore rules
├── pom.xml                # Maven project configuration





Technologies Used

Java (Swing): For creating the graphical user interface.
PostgreSQL: AWS-hosted relational database for storing application data.
Maven: For managing project dependencies and building the application.
iText: For generating PDF invoices.
FlatLaf: Modern UI design for enhancing the application's appearance.


![Screenshot 2024-12-29 193813](https://github.com/user-attachments/assets/41c53f8a-84e8-4f65-aa23-07c714d1e61c)

![Screenshot 2024-12-29 193857](https://github.com/user-attachments/assets/ca3532fc-d814-49df-b678-591feb9c1b6c)






