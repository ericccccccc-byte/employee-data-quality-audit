# Employee Data Quality Audit — Excel Project

## Overview

This project simulates a real-world data cleaning and analysis task performed on a raw HR employee dataset. The goal was to identify all data quality issues, resolve them systematically, document the audit trail, and derive meaningful insights from the cleaned data — all using Microsoft Excel.

This is the kind of work a data analyst is expected to do on day one at any company that receives data from multiple sources.

---

## Tools Used

- Microsoft Excel

## Skills Demonstrated

- Data Cleaning (TRIM, CLEAN, PROPER, LOWER, LEN)
- Handling Missing Values
- Removing Duplicates
- Standardising Text Casing
- Date Formatting
- Data Validation with Custom Error Alerts
- Conditional Formatting
- COUNTIF, SUMIF formulas
- Data Analysis and Summarisation

---

## Dataset

- **Source:** Synthetic HR dataset created for this project
- **Size:** 12 records, 9 columns
- **Columns:** Emp_ID, Full_Name, Department, City, Join_Date, Salary, Phone, Email, Status

---

## Project Structure

The workbook contains 4 sheets:

### Sheet 1 — Raw Data
The original uncleaned dataset with intentional data quality issues highlighted for visibility.

Issues present in the raw data:
- 1 duplicate row (Rahul Verma appears twice with identical details)
- 1 missing join date (Neha Gupta)
- 1 missing phone number (Ankit Jain)
- 1 invalid status value — "unknown" instead of Active or Inactive (Rohan Mehta)
- 1 inconsistent name casing — "VIKAS KUMAR" in all caps

### Sheet 2 — Cleaned Data
The fully cleaned version of the dataset after all issues were resolved. N/A values are highlighted in orange for easy identification.

Cleaning steps applied:
- TRIM(CLEAN()) applied to remove hidden spaces from text columns
- LEN() used to detect phone numbers with incorrect character counts
- PROPER() applied to standardise all name casing
- LOWER() applied to standardise email addresses
- Ctrl+G Special Blanks used to identify and fill all empty cells with N/A
- Find and Replace used to correct the "unknown" status value to N/A
- Remove Duplicates applied on the Email column — 1 duplicate removed
- Date column formatted consistently as DD-MM-YYYY
- Data Validation added to Status column to restrict entries to Active, Inactive, or N/A only

### Sheet 3 — Audit Summary
A formal audit report documenting:
- KPI summary: total records, records after cleaning, issues found, issues resolved, data quality score
- Issue log table listing each problem, the column affected, records impacted, and action taken
- Full list of all cleaning steps applied

### Sheet 4 — Analysis
Key insights derived from the cleaned dataset:
- Headcount by department with percentage of total workforce
- Salary analysis by department showing total, average, and highest salary
- Employee status breakdown (Active, Inactive, N/A)
- 5 written business insights summarising the findings

---

## Key Findings

- Sales has the largest team with 4 employees making up 36.4% of the workforce
- IT department has the highest average salary at 67,500
- Sales has the lowest average salary at 47,250 despite being the largest team
- 72.7% of employees are Active
- Total monthly payroll is 6,01,000 across all departments

---

## How to Use

1. Open `Employee_Data_Quality_Audit.xlsx` in Microsoft Excel
2. Start with Sheet 1 to see the original raw data and identified issues
3. Compare with Sheet 2 to see the cleaned version
4. Review Sheet 3 for the full audit trail
5. Explore Sheet 4 for analysis and business insights

---

## Author

Eric  
Aspiring Data Analyst | Excel · SQL · Python · Power BI  
[GitHub Profile](https://github.com/ericccccccc-byte)
