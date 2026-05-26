# Week 1 – Data Cleaning and Preparation

This project was completed as part of my Data Analytics Internship at DecodeLabs.

The objective of this project was to clean and prepare a raw e-commerce dataset before performing any further analysis. The dataset was examined for missing values, duplicate records, formatting inconsistencies, and data quality issues. The cleaned dataset can now be used for reporting, visualization, and future analytical tasks.

## Dataset Information

- Records: 1200
- Columns: 14
- Dataset Type: E-commerce Transactions

## Tasks Performed

### Missing Value Handling
- Identified missing values in the dataset
- Found missing entries in the `CouponCode` column
- Replaced missing values with **"No Coupon"**

### Duplicate Verification
- Checked for duplicate rows
- Verified uniqueness of all `OrderID` values
- No duplicate records were found

### Data Standardization
- Converted dates into a consistent `YYYY-MM-DD` format
- Removed unnecessary spaces from text fields
- Standardized text formatting for categorical columns

### Data Validation
Verified the accuracy of transaction records by validating:

```text
TotalPrice = Quantity × UnitPrice
```

No inconsistencies were detected.

## Tools Used

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Microsoft Excel

## Results

After cleaning and validation:

- Missing Values: 0
- Duplicate Rows: 0
- Duplicate Order IDs: 0
- Date Formats Standardized
- Text Fields Cleaned
- Data Validation Completed Successfully

## Project Files

- `Data_Cleaning_Project.ipynb` – Jupyter Notebook containing the complete workflow
- `Dataset for Data Analytics.xlsx` – Original dataset
- `cleaned_dataset.csv` – Cleaned dataset in CSV format
- `cleaned_dataset.xlsx` – Cleaned dataset in Excel format

## Key Learnings

This project helped me gain practical experience in:

- Working with real-world datasets
- Handling missing values
- Detecting duplicate records
- Cleaning and standardizing data
- Validating data quality
- Using Pandas for data preprocessing
- Preparing datasets for future analysis

## Author

**Gautam Verma**  
Data Analytics Intern – DecodeLabs
