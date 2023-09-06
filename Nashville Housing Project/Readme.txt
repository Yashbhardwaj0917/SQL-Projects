# Nashville Housing Data Cleaning - SQL Project

This repository contains SQL queries for cleaning and transforming Nashville housing data. The project aims to standardize date formats, populate missing data, break down addresses into individual columns, update field values, remove duplicates, and delete unused columns.

## Table of Contents
1. [Project Overview](#project-overview)
2. [SQL Queries](#sql-queries)
3. [Usage](#usage)
4. [Contributing](#contributing)
5. [License](#license)

## Project Overview
The project focuses on data cleaning tasks for Nashville housing data stored in the `PortfolioProject.dbo.NashvilleHousing` table. The SQL queries included address various data quality issues and standardize the dataset for analysis.

## SQL Queries
### Standardize Date Format
- Converts the `SaleDate` column to the proper date format.

### Populate Property Address Data
- Populates missing `PropertyAddress` values by referencing other rows with the same `ParcelID`.

### Breaking Out Address into Individual Columns
- Splits the `PropertyAddress` column into separate `Address` and `City` columns.
- Splits the `OwnerAddress` column into separate `OwnerSplitAddress`, `OwnerSplitCity`, and `OwnerSplitState` columns.

### Change Y and N to Yes and No
- Updates the values in the `SoldAsVacant` column, changing 'Y' to 'Yes' and 'N' to 'No'.

### Remove Duplicates
- Identifies and selects duplicate rows based on specific columns and keeps only one unique row for each set of duplicates.

### Delete Unused Columns
- Drops columns that are no longer needed in the dataset.

## Usage
To use these SQL queries:

1. Ensure you have access to a SQL database containing the `NashvilleHousing` table.
2. Copy and paste the provided SQL queries into your preferred SQL client or environment.
3. Execute the queries in the order they are presented to clean and transform the dataset.

## Contributing
Contributions to this project are welcome! If you have suggestions for improving existing queries or adding new cleaning tasks, please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as needed.

---

Feel free to customize this README file to include specific details about your dataset, data cleaning tasks, and any other relevant information. Once completed, add the README file to your GitHub repository to provide clear documentation for users and contributors.
