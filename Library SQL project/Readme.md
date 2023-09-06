# Library Management SQL Project

This repository contains SQL queries for a library management system, allowing you to manage books, loans, patrons, and more. The project is designed to work with a SQL database.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Queries](#queries)
3. [Database Schema](#database-schema)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)

## Project Overview
The project aims to create a database system for a library, providing functionalities to manage books, loans, patrons, and generate reports on various aspects of the library's operation. The SQL queries included cover tasks such as checking out and returning books, finding available books, generating reports, and more.

## Queries
The SQL queries in this project are organized into sections based on their functionality. Here are the key query sections:

### Checking Book Availability
- `AvailableBooks`: Calculates the total number of available copies of a specific book.

### Adding New Books
- `INSERT INTO Books`: Adds new books to the library's collection.

### Checking Out Books
- `INSERT INTO Loans`: Records book loans with loan date and due date.

### Checking Due Dates
- `Books Due on Date`: Generates a report of books due back on a specific date with patron contact information.

### Returning Books
- `Return Books`: Marks books as returned in the database.

### Patron Engagement
- `Patrons with Fewest Loans`: Generates a report of patrons who have checked out the fewest books.

### Featured Books
- `Available Books from 1890s`: Creates a list of books from the 1890s that are currently available.

### Book Statistics
- `Books Published Each Year`: Shows the number of books published each year.
- `Most Popular Books`: Lists the 5 most popular books checked out.

## Database Schema
The SQL queries in this project assume a specific database schema with the following tables:
- `Books`: Contains information about books, including title, author, publication year, and more.
- `Loans`: Records book loans, including loan date, due date, and return date.
- `Patrons`: Stores information about library patrons.

Please ensure you have the required tables and data set up in your SQL database before running these queries.

## Usage
To use these SQL queries:

1. Set up a SQL database with the necessary tables (`Books`, `Loans`, `Patrons`) and populate them with data.
2. Copy and paste the queries into your preferred SQL client or environment.
3. Execute the queries to perform various library management tasks and generate reports.

## Contributing
Contributions to this project are welcome! If you have suggestions for improving existing queries or adding new ones, please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as needed.

---

Feel free to customize this README file further based on your project's specific details and requirements. Once you've created your README file, you can add it to your GitHub repository to provide documentation for others who may use or contribute to your project.
