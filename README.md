**Task 1 — Data Cleaning & Preprocessing (Netflix Movies & TV Shows Dataset)**

**Dataset Used:** Netflix Movies and TV Shows (Kaggle)

**Steps Performed :**

1. Loaded the raw dataset into Python (Pandas)

2. Checked missing values using isnull().sum()

3. Filled missing values in key columns (director, cast, country, date_added, rating) with “Unknown”

4. Removed duplicate records using drop_duplicates()

5. Standardized text columns (lowercased + stripped spaces)

6. Converted date_added column to proper datetime format using pd.to_datetime()

7. Normalized all column names using lowercase and underscores

8. Exported the cleaned dataset to netflix_cleaned.csv

**Deliverables :**

  Raw dataset: netflix_titles.csv

  Cleaned dataset: netflix_cleaned.csv

  Python code: notebook/script used for cleaning

  Summary: This README file

**Outcome :**

How to identify and fix missing, inconsistent, and duplicate data

How to perform real-world data cleaning with Pandas

Formatting dates and correcting text data

Preparing a dataset for analysis or machine learning
