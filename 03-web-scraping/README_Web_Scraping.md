# Web Scraping with Requests, BeautifulSoup, and Pandas

## Overview
This project demonstrates introductory web scraping with Python. It explores HTML elements on a practice webpage, extracts a table from a public Wikipedia page, stores the table in a Pandas DataFrame, exports CSV files, and performs basic data checks and numeric-column cleaning.

## What the notebook does
- Sends HTTP requests with a timeout and checks for request errors.
- Parses HTML with BeautifulSoup.
- Practices finding HTML elements and extracting text.
- Extracts a table from the selected Wikipedia page.
- Saves the scraped data to `largest_companies.csv`.
- Checks dataset shape, column names, missing values, and data types.
- Converts revenue, employee counts, and revenue growth to numeric values.
- Saves the cleaned data to `largest_companies_cleaned.csv`.

## Tools
- Python
- Requests
- BeautifulSoup (`beautifulsoup4`)
- Pandas
- Jupyter Notebook

## Setup and usage
1. Install dependencies:
   ```bash
   pip install requests beautifulsoup4 pandas
   ```
2. Open `Web_Scraping_with_BeautifulSoup.ipynb` in Jupyter Notebook.
3. Run the cells from top to bottom. The CSV files are saved in the notebook's current working directory.

## Notes
The notebook uses public webpages for educational practice. Page layouts and table contents can change, so the scraper may need updating if the source HTML changes. Check the website's terms and access rules before reusing scraped content. The notebook has been organized for GitHub, but the cleaned version has not been executed as part of this preparation.
