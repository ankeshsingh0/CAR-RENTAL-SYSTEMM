# CAR RENTAL SYSTEMM

**CAR RENTAL SYSTEMM** is a Java-based desktop application designed to provide a seamless vehicle rental experience. This project features a graphical user interface for customers and admins, built using Java Swing, with PostgreSQL as the database hosted on AWS. The system supports vehicle booking, user management, and administrative controls.

---

## Table of Contents

1. [Features](#features)
2. [Application Overview](#application-overview)
3. [Folder Structure](#folder-structure)
4. [Technologies Used](#technologies-used)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Contributors](#contributors)

---

## Features

### Customer Features
- **Browse Vehicles**: View available vehicles and filter by type or availability date.
- **Book Vehicles**: Easily book vehicles and specify rental dates.
- **View Bookings**: Manage active, completed, or canceled bookings.
- **Notifications**: Receive reminders about booking deadlines.
- **Invoices**: Generate and download PDF invoices for completed bookings.
- **My Account**: Update account details, such as name, phone number, and password.

### Admin Features
- **Manage Vehicles**: Add, edit, or remove vehicles in the fleet.
- **Manage Bookings**: Oversee all bookings, including the ability to cancel them.
- **Generate Reports**: View detailed analytics, such as total revenue, active bookings, and customer statistics.

---

## Folder Structure

```
CAR RENTAL SYSTEMM/
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
```

### Explanation of Key Folders
- **`classes/`**: Contains core entities, such as `User`, `Vehicle`, `Booking`, and `Invoice`.
- **`common/`**: Provides shared utilities, including error handling and input validation.
- **`controllers/`**: Implements the logic for interacting with the PostgreSQL database (e.g., fetching vehicles, bookings, and invoices).
- **`view/`**: Includes GUI components like admin and customer dashboards.
- **`views/`**: Contains additional customer-focused GUIs (e.g., booking notifications).

---

## Technologies Used

- **Java (Swing)**: For creating the graphical user interface.
- **PostgreSQL**: AWS-hosted relational database for storing application data.
- **Maven**: For managing project dependencies and building the application.
- **iText**: For generating PDF invoices.
- **FlatLaf**: Modern UI design for enhancing the application's appearance.

---


---

## Usage

### For Customers:
- **Sign Up**: Register with your details to create a new account.
- **Book a Vehicle**: Browse the available vehicles and book one for your desired dates.
- **Invoices**: View and generate invoices for completed bookings.
- **My Account**: Update your personal information, such as phone number and password.

### For Admins:
- **Manage Vehicles**: Add, update, or delete vehicles in the fleet.
- **View Reports**: Access analytics, such as revenue and active bookings.
- **Manage Bookings**: Oversee all bookings and handle cancellations.

---


