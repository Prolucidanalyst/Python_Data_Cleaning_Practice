# Python_Data_Cleaning_Practice
## Project Title
Data Cleaning and Preparation of a Tech Registration Dataset using Python (Pandas)
## Project Overview
This project focuses on cleaning and preparing a real-world tech training registration dataset using Python and Pandas.
The dataset contained inconsistencies such as:
-  Mixed text formatting (upper/lower case names)
-  Punctuation errors in full names
-  Inconsistent categorical values (e.g., "graphic design" vs "graphics design")
-  Logical duplicates (multiple registrations by the same individual)
-  Missing values in split name columns and phone numbers
The goal of this project was to transform the raw dataset into a clean, analysis-ready dataset.
## Tools and Technologies
-  Python
-  Pandas
-  Jupyter Notebook
## Data Cleaning Process
The following steps were carried out:
-  Standardized text formatting (Conversion of name fields to title case).
-  Removed unwanted punctuation from name fields.
-  Split and recombined name columns while handling missing values.
-  Standardized categorical variables (the package column)
-  Identified and removed logical duplicates based on: Full Name, Package, Local Government Area, and phone number
-  Converted appropriate columns to correct data types(the submit_time column to date time data type from object)
-  Exported the cleaned dataset for further analysis
## Key Learning Outcomes
- Handling logical duplicates using subset-based deduplication
- String manipulation and text normalization
- Managing missing values in concatenated fields
- Cleaning real-world messy registration data
