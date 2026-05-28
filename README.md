# 🎬 Netflix Data Cleaning & Preprocessing
# Task Overview
Task 1 — Data Cleaning and Preprocessing
Clean and prepare the raw Netflix Movies and TV Shows dataset using Python (Pandas).

## Dataset

Source: https://www.kaggle.com/datasets/shivamb/netflix-shows

File: `netflix_titles.csv`

Size: ~8,800 rows × 12 columns

## Tools Used

* Python 3
* Pandas
* Jupyter Notebook

## Steps Performed

| Step | Action                                                                                          |
| ---- | ----------------------------------------------------------------------------------------------- |
| 1    | Loaded dataset and explored shape, datatypes, and summary statistics                            |
| 2    | Identified missing values using `df.isnull().sum()`                                             |
| 3    | Filled missing values in `director`, `cast`, and `duration` columns using placeholder values    |
| 4    | Filled missing values in `country` and `rating` columns using mode values                       |
| 5    | Dropped rows where `date_added` values were missing                                             |
| 6    | Removed duplicate rows using `df.drop_duplicates()`                                             |
| 7    | Standardized column names by converting them to lowercase and replacing spaces with underscores |
| 8    | Removed extra whitespace and standardized text formatting using Title Case                      |
| 9    | Converted `date_added` column to `datetime64` datatype                                          |
| 10   | Ensured `release_year` column was stored as integer datatype                                    |
| 11   | Exported the cleaned dataset as `cleaned_netflix_dataset.csv`                                   |

Summary of Changes

1) Missing values handled across 6 columns
2) Duplicate rows removed (if any)
3) Column names standardised to lowercase with underscores
4) date_added converted from string to proper datetime
5) type column values normalised to Title Case

## Key Learnings

* Gained hands-on experience with essential Pandas functions such as `.isnull()`, `.fillna()`, `.dropna()`, and `.drop_duplicates()` for data cleaning and preprocessing.
* Learned how to identify, handle, and manage missing values using different preprocessing techniques.
* Understood the importance of deciding when to fill missing data and when to remove incomplete records.
* Developed practical understanding of removing duplicate records to improve dataset quality and accuracy.
* Learned the significance of maintaining consistent datatypes for reliable analysis and visualization.
* Understood the importance of standardized column naming conventions for clean, machine-readable datasets.
* Improved understanding of preprocessing raw datasets before performing analysis or building models.
* Built confidence in handling real-world datasets independently using Python and Pandas.



