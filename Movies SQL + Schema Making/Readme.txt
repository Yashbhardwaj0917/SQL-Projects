# Movie Database SQL Project

This repository contains SQL queries and data management tasks related to a movie database. The project includes queries for selecting, filtering, and updating data in the database, as well as challenges to test your SQL skills.

## Table of Contents
1. [Project Overview](#project-overview)
2. [SQL Queries](#sql-queries)
3. [Challenges](#challenges)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)

## Project Overview
The project focuses on managing a movie database with tables such as `movie_basic`, `director`, `critic_rating`, `posters`, and more. SQL queries in this project are designed to retrieve movie data, categorize movies by score, filter movies by criteria, and perform data management tasks like adding, updating, and deleting records.

## SQL Queries
### Selecting Data
- The project begins with simple SQL queries to select data from the `critic_rating` table. Two different approaches are demonstrated for categorizing movies based on critic ratings.

### Challenge: Filter Movies by Score
- This query joins multiple tables (`titles`, `director`, and `critic_rating`) to create a report of movies categorized by critic ratings. Movies are classified as "Amazing," "Good," "Decent," or "Bad" based on their critic ratings and release years.

### Challenge: Fixing Mistakes
- This section includes SQL statements to add new movies, update genre names, and delete records for specific movies directed by Garry Scott for Lionel Brownstone's studio.

### Challenge: Find the Best Film
- The final query retrieves movie data from multiple tables and lists the top 10 movies with the highest critic ratings. It also includes information about the movie's director and a poster filename.

## Usage
To use these SQL queries and tasks:

1. Set up a SQL database with the necessary tables (`movie_basic`, `director`, `critic_rating`, etc.) and populate them with data.
2. Copy and paste the provided SQL queries into your preferred SQL client or environment.
3. Execute the queries to perform various data selection, filtering, and management tasks.

## Contributing
Contributions to this project are welcome! If you have suggestions for improving existing queries or adding new challenges, please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as needed.

---

Customize this README file to include specific details about your project, database schema, and any other relevant information. Once you've created your README file, you can add it to your GitHub repository to provide documentation for others who may use or contribute to your project.
