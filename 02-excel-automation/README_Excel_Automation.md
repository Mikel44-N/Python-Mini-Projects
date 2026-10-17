# Excel Automation with Python

## Overview
This project uses Python and `openpyxl` to automate a basic Excel reporting workflow.

## What it does
- Reads names and ages from an Excel worksheet.
- Filters for people aged 25 or older.
- Sorts the filtered records from oldest to youngest.
- Creates or refreshes an `Automated Report` worksheet.
- Formats the report with a highlighted header, borders, adjusted column widths, and an Excel table.
- Applies conditional formatting to the Age column.
- Saves the updated workbook.

## Tools
- Python
- openpyxl
- Jupyter Notebook
- Microsoft Excel

## Files
- `Excel_Automation_with_Python.ipynb` — the automation notebook.
- `people_automation.xlsx` — the workbook used as the input and updated output.

## How to run
1. Install the dependency: `pip install openpyxl`
2. Keep `people_automation.xlsx` in the same folder as the notebook.
3. Open the notebook in Jupyter and run the cells from top to bottom.

The notebook reads source records from the `Sheet` worksheet and saves the generated report back into `people_automation.xlsx`.
