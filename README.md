# Data-Analytics-Task-1
Data Cleaning and Preprocessing

# Netflix Data Cleaning Project

## Internship Task 1: Data Cleaning and Preprocessing

This project is part of a Data Analyst Internship Task focused on cleaning and preprocessing a real-world dataset. The dataset used for this task is the **Netflix Movies and TV Shows** dataset from Kaggle.

---

## Files Included

- `netflix_titles.csv` — Original raw dataset from Kaggle
- `netflix_cleaned.csv` — Cleaned version of the dataset
- `Netflix.ipynb` — Jupyter Notebook used for cleaning the data
- `README.md` — This summary file

---

## Tasks Completed

### Missing Values
- Used `.isnull()` to identify nulls

### Duplicate Removal
- Used `.drop_duplicates()` to remove duplicate rows

### Text Standardization
- Standardized string columns like `country`, `type`, and `rating` to lowercase and trimmed spaces

### Date Format Consistency
- Converted `date_added` column to `datetime` format using `pd.to_datetime()`

### Column Header Cleanup
- Renamed column headers to lowercase and replaced spaces with underscores

### Data Type Correction
- Verified data types:
  - `release_year` as `int`
  - `date_added` as `datetime`
  - Categorical columns as `object`

---

## Tools Used

- **Python 3**
- **Pandas**
- **Jupyter Notebook**

---

## Outcome

A fully cleaned, well-structured dataset (`netflix_cleaned.csv`) ready for analysis or visualization.
