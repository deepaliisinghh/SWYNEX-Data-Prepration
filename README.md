# Data Preparation and Cleaning – SWYNEX Technologies

## Project Overview
This project focuses on data preparation and cleaning using the Titanic dataset as part of the SWYNEX Technologies internship task.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Dataset
Titanic Dataset – 891 rows and 12 original columns.

## Data Cleaning Steps
1. Loaded and inspected the dataset.
2. Identified missing values.
3. Filled missing Age values using median.
4. Filled missing Embarked values using mode.
5. Dropped Cabin due to excessive missing values.
6. Checked and handled duplicate records.
7. Verified data types.
8. Detected outliers using the IQR method.
9. Retained potential outliers because they may represent valid observations.
10. Exported the cleaned dataset.

## Final Dataset
- Original records: 891
- Original columns: 12
- Final records: 891
- Final columns: 11
- Missing values: 0
- Duplicate records: 0

## Files Included
- `train.csv` – Original dataset
- `data_preparation.ipynb` – Data cleaning notebook
- `cleaned_data.csv` – Cleaned dataset

## Conclusion
The dataset was successfully cleaned and prepared for further analysis using Python and Pandas.