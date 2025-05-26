# Data-Cleaning-and-Preprocessing
# Task 1: Data Cleaning and Preprocessing

## 📅 Task Completed  
*Date:* 2025-05-26  
*Tool Used:* Microsoft Excel  
*Status:* ✅ Completed

## 🎯 Objective  
To clean and prepare a raw dataset by handling missing values, removing duplicates, standardizing formats, and ensuring consistent structure for analysis.

## 🧹 Steps Completed

### 1. Handled Missing Values  
- Identified missing values using Excel filters ((Blanks)).
- Filled missing entries with appropriate placeholders (e.g., "Unknown" for categorical data).
- Removed rows only if data was insufficient for analysis.

### 2. Removed Duplicate Rows  
- Used *Data > Remove Duplicates* in Excel.
- Verified key columns before deleting duplicate records.

### 3. Standardized Text Values  
- Corrected inconsistent text entries (e.g., "MALE", "male" → "Male").
- Used Excel functions:
  - =UPPER() to make text uppercase  
  - =LOWER() for lowercase  
  - =PROPER() to capitalize words  
- Standardized entries in columns like *gender, **country*, etc.

### 4. Formatted Date Values  
- Reformatted all date columns to DD-MM-YYYY.
- Ensured all date values are in proper *date format* (not text).
- Used =DATEVALUE() when conversion was needed.

### 5. Renamed Column Headers  
- Updated all column names to be:
  - In *UPPERCASE*  
  - With *underscores* instead of spaces  
  - Without special characters  
- Example: "Customer Name" → CUSTOMER_NAME

### 6. Checked and Corrected Data Types  
- Ensured numbers (like age, income) are stored as numeric values.
- Dates converted to Excel-recognized date types.
- Text fields formatted consistently.

## ✅ Output  
- A clean, consistent, and structured dataset ready for analysis or visualization.
- File delivered: cleaned_dataset.xlsx

## 📎 Reference  
Based on the standard Data Cleaning Guide and best practices in Excel.


