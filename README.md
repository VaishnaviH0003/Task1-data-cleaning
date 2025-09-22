# Task 1 - Data Cleaning and Preprocessing
**Elevate Labs Internship**

## Dataset
Netflix Movies and TV Shows (Kaggle)

## Cleaning Steps
- Missing values handled:
  - Director → "Unknown"
  - Cast → "Not Specified"
  - Country → "Not Specified"
  - Rating → "Unrated"
  - Dropped nulls in `date_added`
- Removed duplicates (XX rows dropped)
- Standardized text: 
  - Country → Capitalized
  - Type → Movie / TV Show
- Date formatting:
  - Converted `date_added` to datetime
  - Extracted `year_added` & `month_added`
- Renamed columns → lowercase + underscores
- Corrected data types:
  - release_year → int
  - date_added → datetime

## Deliverables
- Raw dataset → raw_data/netflix_titles.csv
- Cleaned dataset → cleaned_data/cleaned_netflix.csv
- Notebook → notebook/task1_cleaning.ipynb
