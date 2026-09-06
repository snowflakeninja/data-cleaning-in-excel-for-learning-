# Excel Data Cleaning Practice Project

This project is a hands-on Excel data cleaning exercise created as part of my learning and practice in data analysis.

The objective of the project was to take a small employee dataset containing inconsistent and unclean data, identify the data quality issues, clean the dataset using Excel functions and tools, and create a final structured dataset ready for further analysis.

## Project Objective

The main goals of this project were to practice:

- Identifying data quality issues
- Cleaning text values
- Standardizing employee information
- Handling missing values
- Cleaning numeric data
- Standardizing email and city information
- Identifying duplicate records
- Creating a separate final cleaned dataset

## Dataset

The practice dataset contains employee information such as:

| Column | Description |
|---|---|
| Employee ID | Unique identifier for an employee |
| Employee Name | Employee name |
| Department | Employee department |
| Salary | Employee salary |
| Email | Employee email address |
| City | Employee city |

The original data intentionally contains formatting inconsistencies and other data quality issues for cleaning practice.

## Data Cleaning Process

### 1. Employee ID Cleaning

Employee IDs were checked and standardized to remove unwanted formatting and inconsistencies.

### 2. Employee Name Cleaning

Employee names were cleaned and standardized using Excel text functions.

This included tasks such as:

- Removing unnecessary spaces
- Correcting inconsistent capitalization
- Standardizing name formatting

### 3. Department Standardization

Department values were reviewed and standardized so that different representations of the same department could be treated consistently.

### 4. Salary Cleaning

Salary values were cleaned to ensure that they could be treated as numeric values in Excel.

This included handling unwanted characters, spaces, and invalid values.

### 5. Email Cleaning

Email addresses were cleaned and standardized to make their formatting consistent.

### 6. City Cleaning

City names were cleaned to remove inconsistencies in spacing and capitalization.

### 7. Missing Value Handling

The dataset was checked for missing or incomplete values and appropriate cleaning logic was applied where required.

### 8. Duplicate Detection

Duplicate employee records were identified before producing the final cleaned dataset.

### 9. Final Clean Dataset

After completing the cleaning process, the cleaned columns were used to create a separate final dataset.

This provides a clear distinction between:

- Original raw data
- Cleaning and validation work
- Final cleaned data

## Excel Functions and Tools Practiced

The project provided hands-on practice with Excel features and functions including:

- `TRIM`
- `CLEAN`
- `UPPER`
- `LOWER`
- `PROPER`
- `LEN`
- `SUBSTITUTE`
- `VALUE`
- `IF`
- `IFERROR`
- `TEXTBEFORE`
- `TEXTAFTER`
- Find and Replace
- Remove Duplicates
- Data validation and checking
- Excel Tables

## Workbook Structure

The workbook contains the original data, intermediate cleaning work, and the final cleaned dataset.

The main data-cleaning sheets are:

```text
cleaning sample dataset
cleaned_dataset
```

### `cleaning sample dataset`

Contains the original employee data along with additional columns used to clean and validate the records.

Examples of cleaning columns include:

```text
CLEAN_EMPLOYEE_ID
STATUS
CLEAN_EMPLOYEE_NAME
CLEAN_DEPARTMENTS
CLEAN_SALARY
CLEAN_EMAIL
CLEAN_CITY
DUPLICATE_STATUS
```

### `cleaned_dataset`

Contains the final cleaned employee dataset after the data quality issues were addressed.

## Project File

```text
excel-data-cleaning/
│
├── data_cleaning.xlsx
└── README.md
```

## Key Learning Outcomes

Through this project, I practiced how to approach data cleaning as a structured process rather than directly modifying values without validation.

The general workflow followed was:

```text
Raw Data
   |
   v
Identify Data Quality Issues
   |
   v
Create Cleaning Columns
   |
   v
Clean and Standardize Values
   |
   v
Check Missing and Invalid Data
   |
   v
Identify Duplicates
   |
   v
Validate Results
   |
   v
Create Final Clean Dataset
```

This project helped reinforce the importance of keeping the original data available while performing transformations in separate columns before creating the final cleaned dataset.

## Future Practice

As I continue learning Excel and data analysis, I plan to extend this type of project with:

- Larger datasets
- More complex duplicate handling
- Date cleaning and standardization
- Data validation rules
- Conditional formatting for data quality checks
- Power Query for repeatable data cleaning
- Combining data from multiple tables
- Automated cleaning workflows

## Tools Used

- Microsoft Excel

