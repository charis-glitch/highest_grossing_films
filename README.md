# Highest-Grossing Films — Web Scraping & Data Cleaning Project

## Overview
This project demonstrates my ability to **extract structured data directly from an HTML webpage**, clean and standardize it using **Pandas**, and create **data visualizations**.  
The dataset is collected live from the Wikipedia page *“List of highest-grossing films”* using `requests` and `pandas.read_html`.

---

## What I Did
### **1. Web Scraping (HTML → DataFrame)**
- Requested the webpage using a custom User-Agent.
- Parsed all `<table>` elements from the HTML using `pandas.read_html`.
- Selected the main film-grossing table for analysis.

### **2. Data Cleaning**
- Inspected missing values and duplicates.
- Standardized the dataset for analysis and export.

### **3. Exploratory Analysis**
- Extracted the **Top 10 worldwide highest-grossing films**.
- Created a bar chart visualizing global box-office totals.
- Exported the cleaned dataset as `highest_grossing_films_cleaned.csv`.

---

## Skills Demonstrated
- **Web Scraping (HTML parsing)**
- **Requests + HTTP headers**
- **Pandas data cleaning**
- **Handling messy table structures**
- **Data inspection & type correction**
- **Matplotlib & Seaborn visualization**
- **CSV exporting**

---

## Output Files
- `highest_grossing_films_cleaned.csv` — cleaned dataset  
- `top_10.png` — visualization of top 10 highest-grossing films  
- `highest_grossing_films_cleaning.ipynb` - Full analysis notebook / script in this repo

