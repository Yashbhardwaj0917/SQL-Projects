# Restaurant Anniversary SQL Project

This repository contains SQL queries and data management tasks related to a restaurant's anniversary celebration. The project includes queries for creating party invitations, managing party attendees, printing a menu, signing up customers for a loyalty program, updating customer information, removing customer records, logging customer responses, looking up reservations, taking reservations and delivery orders, tracking customer favorites, and generating a report of the top 5 customers.

## Table of Contents
1. [Project Overview](#project-overview)
2. [SQL Queries](#sql-queries)
3. [Usage](#usage)
4. [Contributing](#contributing)
5. [License](#license)

## Project Overview
The project simulates various tasks and interactions within a restaurant, such as managing customer data, reservations, orders, and customer preferences. It also includes SQL queries to generate reports for restaurant operations.

## SQL Queries
### Create Invitations for a Party
- Selects customer information for party invitations.

### Create a Table to Store Information
- Creates a table called `PartyAttendees` to store party attendee information with a foreign key reference to the `Customers` table.

### Print a Menu
- Selects and displays menu items, including appetizers, beverages, and all items sorted by price.

### Sign a Customer Up for Your Loyalty Program
- Inserts a new customer into the `Customers` table with loyalty program details.

### Update Customer Personal Information
- Updates the address, city, and state information for a specific customer.

### Remove Customer Record
- Deletes a specific customer record from the `Customers` table.

### Log Customer Responses
- Inserts party attendance information into the `PartyAttendees` table.

### Look Up Reservations
- Retrieves reservation details along with customer information for customers with last names starting with 'Ste'.

### Take a Reservation
- Inserts a new reservation into the `Reservations` table for a specific customer.

### Take a Delivery Order
- Checks if a customer exists, creates an order, and adds order dishes, calculating the total cost.

### Track Customer Favorite
- Updates a customer's favorite dish in the `Customers` table.

### Report of Top 5 Customers
- Generates a report of the top 5 customers based on the number of orders they've placed.

## Usage
To use these SQL queries:

1. Set up a SQL database with the necessary tables (`Customers`, `Dishes`, `Orders`, `Reservations`, etc.) and populate them with data.
2. Copy and paste the provided SQL queries into your preferred SQL client or environment.
3. Execute the queries to perform various tasks and generate reports related to restaurant operations.

## Contributing
Contributions to this project are welcome! If you have suggestions for improving existing queries or adding new restaurant-related tasks, please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as needed.

---

Customize this README file to include specific details about your restaurant, database schema, and any other relevant information. Once you've created your README file, you can add it to your GitHub repository to provide clear documentation for users and contributors.
