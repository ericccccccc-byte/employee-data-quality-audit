# Employee Data Quality Audit (Microsoft Excel)

A complete Excel project focused on cleaning messy HR data, documenting every issue found, and analysing the cleaned dataset to generate business insights.

The objective of this project was to practise the kind of data quality checks and cleaning tasks that are commonly performed before any business analysis can begin.

---

## Project Objective

Raw business data often contains duplicates, missing values, inconsistent formatting, and invalid entries. In this project, I started with an intentionally messy HR dataset and performed a complete data quality audit using Microsoft Excel.

The project includes:

- Identifying data quality issues
- Cleaning and standardising the dataset
- Recording every cleaning action in an audit report
- Analysing the cleaned data to generate business insights

---

## Tools Used

- Microsoft Excel

---

## Excel Skills Demonstrated

- Data Cleaning
- Data Validation
- Conditional Formatting
- Duplicate Detection & Removal
- Missing Value Handling
- Text Standardisation
- Date Formatting
- Data Quality Auditing
- Basic Data Analysis

### Excel Functions Used

- TRIM()
- CLEAN()
- PROPER()
- LOWER()
- LEN()
- COUNTIF()
- SUMIF()

---

## Dataset Information

| Item | Details |
|------|---------|
| Dataset | Synthetic HR Employee Dataset |
| Records | 12 |
| Columns | 9 |
| Workbook Sheets | 4 |

Columns included:

- Employee ID
- Full Name
- Department
- City
- Join Date
- Salary
- Phone Number
- Email
- Status

---

# Workbook Structure

## Sheet 1 — Raw Data

Contains the original dataset with multiple data quality issues intentionally introduced.

Issues identified:

- Duplicate employee record
- Missing Join Date
- Missing Phone Number
- Invalid Status value
- Inconsistent text casing

---

## Sheet 2 — Cleaned Data

After identifying every issue, the dataset was cleaned using Excel functions and built-in tools.

Cleaning steps performed:

- Removed extra spaces using **TRIM()** and **CLEAN()**
- Standardised employee names using **PROPER()**
- Converted email addresses to lowercase using **LOWER()**
- Checked phone number lengths using **LEN()**
- Replaced blank values with **N/A**
- Corrected invalid status values
- Removed duplicate records
- Applied consistent date formatting
- Added Data Validation to prevent invalid Status entries

---

## Sheet 3 — Audit Summary

A complete audit report documenting the cleaning process.

Includes:

- Total records
- Records after cleaning
- Number of issues identified
- Number of issues resolved
- Data Quality Score
- Issue Log
- Cleaning Steps Performed

---

## Sheet 4 — Analysis

Performed summary analysis on the cleaned dataset.

Analysis includes:

- Employee count by department
- Department-wise salary analysis
- Employee status distribution
- Monthly payroll
- Business insights

---

# Key Insights

- Sales is the largest department with **4 employees (36.4%)**
- IT has the highest average salary (**67,500**)
- Sales has the lowest average salary (**47,250**)
- **72.7%** of employees are Active
- Total monthly payroll is **₹6,01,000**

---

# Files Included

```
Employee_Data_Quality_Audit.xlsx
README.md
```

---

# What I Learned

Through this project I practised the complete workflow of preparing raw data for analysis. Instead of only cleaning the dataset, I also documented every issue, maintained an audit trail, and generated business insights from the final cleaned data. This project helped strengthen my understanding of Excel functions, data quality principles, and structured data analysis.

---

## Author

**Eric**

Aspiring Data Analyst

**Skills:** Excel • SQL • Python • Power BI

GitHub:
https://github.com/ericccccccc-byte
