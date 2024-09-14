# Pyhton-Call-List-DataCleaning-Project-Using-Pandas

# Project Overview 

This project focuses on cleaning and preprocessing a call list dataset using Python and Pandas. The dataset contained various inconsistencies such as null values, duplicates, and text-related issues. Advanced data cleaning tasks, such as formatting phone numbers into a standard format and splitting address data into separate columns, were also performed to ensure data quality and consistency.

# Steps Involved

# 1. Data Cleaning
Loading Data: Imported the dataset using Pandas.
Handling Missing Values:
Identified columns with null values.
Removing Duplicates: Detected and removed duplicate entries to ensure data uniqueness.

# Text Formatting:
Standardized text formats by trimming whitespace and converting text to lowercase.
Replaced unreliable characters using the replace function.
Stripped unnecessary whitespace using the strip function.

# 2. Advanced Data Cleaning

Phone Number Formatting:
Used regular expressions (regex) to identify and format phone numbers into a consistent format (e.g., (123) 456-7890).
Ensured all phone numbers adhered to the specified format, handling various input formats and correcting errors.

Splitting Address Data:
Split the address data into separate columns for city, state, and street address.
Used string manipulation techniques to accurately extract and assign the correct parts of the address to each column.

# 3. Data Type Adjustments
Converting Data Types: Converted data types to appropriate formats for better performance and compatibility (e.g., converting date strings to datetime objects).

# 4. Additional Cleaning
Removing Irrelevant Columns: Dropped columns that were not useful for analysis.

# Tools and Technologies
Python: The primary programming language used for the project.
Pandas: For data manipulation and cleaning.
Regex: For advanced text formatting and validation.

# Conclusion
This project successfully cleaned and preprocessed the call list dataset, ensuring high data quality and consistency. The cleaned dataset is now ready for further analysis and can be used to derive meaningful insights about call patterns and customer information.

