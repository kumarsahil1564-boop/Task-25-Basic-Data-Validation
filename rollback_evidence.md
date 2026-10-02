# Rollback Evidence

## Purpose
If an incorrect validation rule or data entry is introduced, restore the previous validated template.

## Recovery Procedure
1. Keep a copy of the original `employee_data_validation.xlsx`.
2. Before major edits, duplicate the workbook with a dated backup name.
3. If a validation rule is accidentally changed, replace the edited workbook with the last verified backup.
4. Re-test dropdowns, age, date, Employee ID, and salary validation.

## Evidence
The submitted workbook contains the validated template and a separate `Validation Rules` sheet documenting the intended rules. This provides a reference for restoring the configuration.
