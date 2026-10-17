# Automated Sales Email Report

## Overview
This project automates a sales reporting workflow using Python. It reads transaction data from a CSV file, calculates key metrics, exports an Excel summary, and emails the report as an attachment through Gmail SMTP.

## Features
- Reads sales records from `sales_data.csv` with Pandas.
- Calculates total sales, transaction count, average sale, and best-selling product.
- Exports the summary to `sales_report.xlsx`.
- Emails the Excel report as an attachment.
- Uses environment variables or interactive prompts for email settings rather than hard-coded credentials.

## Tools
- Python
- Pandas
- openpyxl
- `smtplib` and Python's `email` package

## Project files
- `Automated_Sales_Email_Report.ipynb` — main notebook.
- `sales_data.csv` — input transaction data.
- `README.md` — project documentation.
- `sales_report.xlsx` — generated output; created when the notebook runs.

## Setup
Install the required packages:

```bash
pip install pandas openpyxl
```

Place `sales_data.csv` in the same folder as the notebook. The CSV must contain `Product` and `Sales` columns.

Configure these environment variables if preferred:
- `EMAIL_ADDRESS` — sender's Gmail address.
- `EMAIL_APP_PASSWORD` — Gmail App Password.
- `EMAIL_RECIPIENT` — destination email address.

If variables are not set, the notebook prompts for the addresses and securely prompts for the App Password. Use a Gmail App Password, not your normal Gmail password. Never commit credentials to GitHub.

## Run
Open the notebook in Jupyter and run cells from top to bottom. The final cell sends a real email through Gmail SMTP, so check the recipient address before running it.

## Note
The notebook was prepared for GitHub, but its SMTP email-sending step has not been tested as part of this cleanup. Gmail account settings and App Password configuration can affect delivery.
