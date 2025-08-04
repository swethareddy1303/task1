 Task 1: Data Cleaning and Preprocessing
Internship Project – Data Analyst Role

🗂️ Dataset Used
Customer Personality Analysis – A marketing dataset containing customer demographics, purchases, and campaign acceptance data.

🎯 Objective
Clean and prepare a raw dataset by:

Handling missing values

Removing duplicates

Standardizing inconsistent data formats

Formatting dates and fixing data types

Renaming columns for uniformity

🧰 Tools Used
Python (Pandas, NumPy)

Jupyter Notebook

✅ Cleaning Steps Performed
Missing Values:

Detected missing values in the Income column.

Filled missing income values with the median.

Duplicate Handling:

Checked for and removed duplicate rows (if any).

Date Formatting:

Converted the Dt_Customer column from string to datetime format.

Extracted year_joined and month_joined features from it.

Text Standardization:

Standardized Marital_Status by grouping similar or inconsistent values into Single and Married.

Column Renaming:

Renamed all column headers to lowercase and replaced spaces with underscores for consistency.

Data Type Fixes:

Ensured columns like income, year_birth, and dt_customer have the correct data types.



Python code included in: Untitled.ipynb (Jupyter Notebook)

📝 Summary
This preprocessing step ensures that the data is ready for analysis or machine learning by resolving inconsistencies, missing data, and formatting issues.
