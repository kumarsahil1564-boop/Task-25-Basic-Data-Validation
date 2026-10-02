# Task 25 – Basic Data Validation

## Objective
Create a data-entry sheet with dropdowns and validation rules to improve spreadsheet data quality.

## Tools
- Microsoft Excel
- Google Sheets

## Deliverables
- `employee_data_validation.xlsx` – validated employee data-entry template
- `sample_employee_data.csv` – sample employee entries
- `validation_rules.md` – validation rules and purpose
- `deployment_config.md` – deployment/usage configuration
- `rollback_evidence.md` – rollback evidence and recovery approach

## Validation Implemented
1. Employee ID follows `EMP001` style and must be unique.
2. Department uses a controlled dropdown.
3. Gender uses a controlled dropdown.
4. Age is restricted to 18–60.
5. Joining Date is restricted to a valid date range.
6. Employment Type uses a controlled dropdown.
7. Salary must be greater than zero.

## Outcome
The template reduces invalid, inconsistent, and duplicate entries by applying controlled input rules before data is accepted.

## Interview Questions
**Why use data validation?**  
To prevent invalid or inconsistent values and improve spreadsheet data quality.

**What problems can dropdowns prevent?**  
They prevent spelling variations and values outside the approved categories, making filtering and analysis more reliable.
