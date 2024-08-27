



# Car Rental System

## Overview

The **Car Rental System** is a Java-based software application designed to allow users to rent vehicles from a car rental company. This system uses object-oriented programming (OOP) principles to manage different aspects of a car rental business. The project includes modules for vehicle management, customer management, reservations, rental transactions, and billing. It is a comprehensive solution that demonstrates the application of core OOP concepts in a real-world scenario.

## Key Concepts

This project demonstrates the use of fundamental OOP principles:

1. **Encapsulation**: Protects the internal state of objects and exposes only necessary information. Classes such as `Vehicle`, `Customer`, and `RentalTransaction` encapsulate their attributes and provide methods to access and manipulate data.

2. **Inheritance**: Promotes code reuse by allowing classes to inherit properties and behaviors. For instance, `Car`, `Truck`, and `SUV` are subclasses that inherit from the base class `Vehicle`.

3. **Polymorphism**: Enables the system to treat objects as instances of their parent class rather than their actual class. This allows handling different vehicle types through a common interface.

4. **Abstraction**: Simplifies complex systems by modeling classes that are appropriate to the problem while hiding unnecessary details. The system uses abstract classes and interfaces to define common behavior without implementing all specifics.

## Modules

### 1. Admin
- Admin users can access and manage all information in the system.
- Admins have the ability to add new members, update existing information, and search based on various criteria.

### 2. Customer
- Customers can sign in to the system.
- Allows customers to browse available vehicles and rent a car.

### 3. Vehicle Management
- Manages different types of vehicles available for rent (e.g., cars, trucks, SUVs).
- Tracks the current status of each vehicle (e.g., available, rented, under maintenance).
- Allows adding, updating, and removing vehicles from the inventory.

### 4. Customer Management
- Stores customer details, including contact information and rental history.
- Supports functionalities to add, update, and delete customer records.

### 5. Reservation and Booking
- Customers can search for available vehicles.
- Supports reservation and booking of vehicles.
- Keeps track of current reservations and bookings.

### 6. Rental and Billing
- Manages rental transactions, including rental duration and vehicle returns.
- Calculates rental fees based on vehicle type and duration of rental.
- Processes payments and generates invoices.

### 7. User Management
- Manages user authentication and authorization.
- Handles user-related tasks such as login, signup, and role assignment.

## Class Structure

- `Vehicle` (abstract class): Base class for vehicle-related operations.
  - `Car`, `Truck`, `SUV`: Subclasses that represent specific vehicle types.
- `Customer`: Represents a customer, storing personal details and rental history.
- `Admin`: Represents an admin user with enhanced permissions.
- `RentalTransaction`: Handles the details of each rental, including rental duration and fee calculation.
- `Reservation`: Manages vehicle reservation and booking processes.
- `UserManagement`: Manages user accounts, authentication, and authorization.

## Getting Started

### Prerequisites
- **Java Development Kit (JDK)**: Version 8 or later.

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/car-rental-system.git
   cd car-rental-system
   ```

2. **Compile and Run**:
   - Compile the Java source files:
     ```bash
     javac *.java
     ```
   - Run the main application:
     ```bash
     java RentalSystem
     ```

### Usage

- **Admin Functions**: Login as an admin to manage vehicles, customers, and rental transactions.
- **Customer Functions**: Customers can sign up, browse available vehicles, make reservations, and manage their rental history.

## Future Enhancements

- Develop a graphical user interface (GUI) for a more interactive user experience.
- Implement persistent storage using a database such as MySQL.
- Enhance reporting features for admins to track business performance.
- Integrate with third-party payment gateways for real-world payment processing.


