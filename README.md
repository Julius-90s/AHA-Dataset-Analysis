# AHA Dataset Analysis

## Project Overview
This project analyses the American Hospital Association (AHA) hospital dataset containing 1,300 hospital records and 21 original variables.

The aim is to examine hospital operational characteristics and identify patterns in hospital capacity and activity.

## Dataset
The original dataset is stored in the `data` folder.

- `AHA_1300_Database.xlsx` – Original dataset.
- `AHA_Cleaned_Dataset.xlsx` – Cleaned dataset prepared for analysis.

## Data Cleaning
The dataset was loaded into Python using Pandas.

Cleaning activities included:
- Checking the dataset structure and column names.
- Inspecting missing values.
- Investigating the `Births` and `Births or Not` columns.
- Creating a corrected indicator called `Births or Not Clean`.
- Preserving the original indicator column.
- Creating an analysis-ready dataset with 1,300 records, 21 columns and no missing values.

## Descriptive Statistics
The analysis focused on three continuous operational variables:

| Variable | Mean | Median | Range | Standard Deviation |
|---|---:|---:|---:|---:|
| Beds | 200.64 | 120 | 2,393 | 229.39 |
| Admissions | 8,089.82 | 3,453.50 | 133,220 | 11,174.67 |
| Census | 134.36 | 72.50 | 1,953 | 174.84 |

## Visualizations
The analysis includes:
- Histograms for Beds, Admissions and Census.
- Box plots for the three operational variables.

## Tools Used
- Python
- Google Colab
- Pandas
- Matplotlib
- GitHub

## Repository Structure
- `data/` – Original and cleaned Excel datasets.
- `notebooks/` – Python analysis notebook.
- `README.md` – Project documentation.

## Conclusion
The descriptive statistics indicate considerable variation in hospital capacity and activity. For all three operational variables, the mean is higher than the median, suggesting that some hospitals have substantially higher values than others.
