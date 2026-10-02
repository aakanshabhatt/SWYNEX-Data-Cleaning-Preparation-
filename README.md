# SWYNEX Data Cleaning & Preparation

## Project Overview

This project was completed as part of my Data Analyst internship with SWYNEX Technologies.

The objective was to clean and prepare a raw employee dataset for analysis using Microsoft Excel and Power Query.

## Dataset

- Records: 1,020 employees
- Tool Used: Microsoft Excel Power Query

## Data Cleaning Performed

### 1. Employee ID
- Checked for duplicate Employee IDs.
- No duplicate Employee IDs were found.

### 2. Missing Values
- Identified missing values in Age, Salary, and Phone Number.
- Missing values were retained as null where reliable replacement values were not available.

### 3. Salary
- Converted `N/A` values to null.
- Converted Salary to Decimal Number.
- 24 salary values were missing and retained as null.

### 4. Age
- Converted Age to Whole Number.
- 209 age values were missing and retained as null.
- Available ages ranged from 25 to 40.

### 5. Department and Region
- Split the combined Department-Region field into separate Department and Region columns.

### 6. Phone Number
- Removed invalid negative signs from phone numbers.
- Converted Phone Number to Text.
- Identified phone numbers with fewer than 10 digits.
- 92 invalid or incomplete phone numbers were converted to null.
- Valid phone numbers were retained as 10-digit values.

### 7. Joining Date
- Converted Joining Date from Text to Date format.
- Verified that the column contained no errors or empty values.

### 8. Performance Score
- Kept Performance Score as Text because the values were categorical ratings such as Poor, Average, and Excellent.

### 9. Remote Work
- Verified the Remote Work field containing True/False values.

## Final Result

The dataset was cleaned and prepared for further analysis while preserving employee records and avoiding unsupported assumptions when handling missing information.

## Tools Used

- Microsoft Excel
- Power Query

## Key Learnings

- Handling missing and inconsistent data
- Data type conversion
- Splitting columns using delimiters
- Identifying invalid values
- Applying conditional transformations
- Preparing raw data for analysis
