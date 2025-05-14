## Project Structure

This repository includes 3 functional branches, each representing a pipeline phase:

### `1_doc-automation`
Automates daily generation of Word report templates. Includes logic for dynamic folder creation, templating, and email scheduling using PowerShell and Google Apps Script.

### `2_archive-to-csv`
Parses and cleans archived report files. Extracts structured data into normalized CSV format ready for SQL import or Excel sheets.

### `3_analytics-insights`
Connects cleaned data to Tableau. Performs analysis on office workloads, doctor schedules, and test distributions. Includes interactive dashboards.



