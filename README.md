# Data Cleaning & Preprocessing – Global Layoffs Dataset (2020–2023)
## Project Overview
In this project, I cleaned and preprocessed a global layoffs dataset (2020–2023) consisting of 2,000 rows using SQL. The goal was to prepare the data for accurate and reliable analysis by addressing quality issues and ensuring consistency across the dataset. The following steps were performed:
## Cleaning Steps
<P> •	Removed duplicates to eliminate repeated records and ensure data integrity. </P>
<p> •	Handled missing and blank values by filtering out null entries and using appropriate replacement strategies where necessary. </p>
<p> •	Standardized categorical values to ensure consistent formatting (e.g., company names, country names, job titles). </p>
<p> •	Trimmed whitespace and cleaned string fields to avoid discrepancies caused by leading/trailing spaces. </p>
<p> •	Converted date fields to a consistent DATE format to enable time-based analysis. </p>
<p> •	Filtered out irrelevant or inconsistent rows, such as negative layoff numbers or future-dated entries. </p>
<p> •	Normalized column formats (e.g., lowercasing text, unifying abbreviations). </p>
<p> •	Verified data types and applied appropriate conversions (e.g., VARCHAR to INT, FLOAT, or DATE where needed). </p>

## Tools & Environment: SQL (used via MySQL)

Focused on ensuring data accuracy, consistency, and usability for downstream analysis or visualization.
This preprocessing phase set the foundation for meaningful analysis, ensuring the dataset was clean, well-structured, and ready for further exploratory analysis or predictive modeling.

- <a href= "https://github.com/goddy201/Global-Layoffs-Data-Cleaning/blob/main/Global_Layoffs_Dataset.csv"> Dataset</a>
- <a href= "https://github.com/goddy201/Global-Layoffs-Data-Cleaning/blob/main/global%20layoff%20query.sql"> Query</a>
