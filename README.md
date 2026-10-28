<<<<<<< HEAD
# Data Cleaning & Quality Checker

## 1. Project Overview

The Data Cleaning & Quality Checker is a Python-based data analysis project designed to identify data quality issues, clean customer records, validate data, and generate quality reports.

The project uses Python and popular data analysis libraries to improve the consistency, accuracy, and usability of customer data.

## 2. Project Objectives

- Identify missing values in customer records.
- Detect and remove duplicate records.
- Standardize column names and categorical values.
- Validate customer ages.
- Validate email address formats.
- Generate data quality reports.
- Visualize data quality issues using charts.
- Export cleaned data into CSV and Excel formats.

## 3. Technologies Used

- Python
- pandas
- NumPy
- Matplotlib
- openpyxl
- Jupyter Notebook
- Visual Studio Code

## 4. Dataset Description

The project uses a sample customer dataset containing the following fields:

| Column | Description |
|---|---|
| customer_id | Unique customer identifier |
| name | Customer name |
| email | Customer email address |
| age | Customer age |
| city | Customer city |
| annual_income | Customer's annual income |
| signup_date | Customer registration date |

The sample dataset intentionally includes missing values, duplicate records, inconsistent city capitalization, and an invalid age to demonstrate data cleaning techniques.

## 5. Main Features

### Data Inspection
Examines dataset dimensions, column names, data types, and statistical summaries.

### Missing Value Analysis
Identifies missing values and calculates their percentages.

### Duplicate Detection
Detects duplicate records and removes repeated rows.

### Data Standardization
Standardizes city names, column names, and date formats.

### Data Validation
Checks age values against the project's defined age range and validates email formats.

### Automated Quality Reporting
Generates a summary of missing values, duplicates, invalid ages, and email validation results.

### Data Visualization
Creates charts for missing values, email validation results, and annual income distribution.

### Data Export
Exports the cleaned dataset and quality reports into CSV and Excel files.

## 6. Data Cleaning Rules

- Duplicate rows are removed.
- City names are standardized using title case.
- Column names are converted to lowercase.
- Signup dates are converted to datetime format.
- Missing email addresses are preserved as missing.
- Missing ages are preserved as missing.
- Ages outside the defined range of 0–120 are treated as invalid and converted to missing values.
- Email addresses are checked using a regular expression.

The age range is a validation rule selected for this sample project. Email format validation does not confirm whether an email address exists or can receive messages.

## 7. Installation

Install Python and Visual Studio Code, then open the project folder in VS Code.

Open the integrated terminal and install the required libraries:

```bash
pip install -r requirements.txt
```

## 8. How to Run

1. Open the project folder in Visual Studio Code.
2. Open `notebooks/Data_Cleaning_Quality_Checker.ipynb`.
3. Select a Python kernel.
4. Run the notebook cells in order, from the beginning to the end.
5. Review the cleaning results and visualizations.
6. Check the generated files in the `output` folder.

If the notebook is stored in the main project folder instead of `notebooks`, open it from its actual location.

## 9. Output Files

- `cleaned_customers.csv` — cleaned customer dataset in CSV format.
- `cleaned_customers.xlsx` — cleaned customer dataset in Excel format.
- `data_quality_report.csv` — data quality summary.
- `automated_quality_report.csv` — output from the automated quality-check function.
- `missing_values_chart.png` — missing values visualization.
- `email_validation_chart.png` — email validation visualization.
- `annual_income_histogram.png` — annual income distribution histogram.

## 10. Limitations

- The project uses a small sample dataset.
- Data is stored in local files rather than a database.
- Email validation checks format only.
- The age validation range is a project-specific rule.
- Automated checks report data quality issues but do not automatically resolve every possible issue.

## 11. Future Improvements

- Add a graphical user interface.
- Support user-uploaded CSV and Excel files.
- Add configurable validation rules.
- Generate a PDF quality report.
- Add more advanced anomaly detection.
- Store datasets and reports in a database.

## 12. Conclusion

This project demonstrates practical data cleaning, validation, exploratory analysis, visualization, and reporting using Python. It provides a foundation for understanding data quality management in real-world data analysis workflows.
=======
# data-cleaning-quality-checker-python
Python project for data cleaning, validation, quality reporting, and visualization
>>>>>>> 73d24e0d47f067e9199d6fa6a73777d653f010fd
