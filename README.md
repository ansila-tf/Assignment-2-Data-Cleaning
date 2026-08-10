Assignment 2 – Data Cleaning

This assignment focuses on cleaning and transforming an uncleaned dataset using Power Query.

Data Cleaning Steps

1. Handling Missing Values

* Price Column: Cleaned the data using Capitalize and Trim, calculated the median, and replaced null values with the median value.
* Category Column: Standardized the text, corrected spelling mistakes, grouped the categories to identify the most frequent category (Electronics), and replaced null values with Electronics.

2. Correcting Inconsistent Data

Standardized the Product Name using Capitalize and Trim, and corrected spelling mistakes in the Category column.

3. Removing Duplicates

Used Remove Duplicates to remove 3 duplicate rows, reducing the dataset from 34 to 31 rows.

4. Splitting and Merging Data

Split the Product ID into Manufacturing Date and Country Code, and merged Brand Name and Product Name into Product Brand.

5. Number Formatting

Formatted the Price column as Currency and used Using Locale (English – United Kingdom) to format Manufacturing Date as DD-MM-YYYY.

6. Conditional Formatting

Applied a Data Bar to the Price column and created a custom rule to highlight Electronics in the Category column.
