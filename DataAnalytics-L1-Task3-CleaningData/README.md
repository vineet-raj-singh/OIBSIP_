# Data Cleaning Analysis

## Objective
Clean and transform a messy retail sales dataset into a structured and analysis-ready dataset using Python and Pandas.

## Dataset
Retail Store Sales: Dirty for Data Cleaning

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Cleaning Performed

### 1. Data Quality Analysis
- Checked dataset shape and columns
- Checked missing values
- Checked duplicate rows
- Checked data types
- Reviewed numerical statistics and value ranges

### 2. Missing Value Handling
Missing values were analyzed column-wise.

- Numerical columns were handled using median values.
- Text/categorical columns were handled using the mode.
- This helped preserve the available data without unnecessary row deletion.

### 3. Duplicate Removal
Duplicate rows were identified and removed from the dataset.

### 4. Standardization
- Leading and trailing spaces were removed from text values.
- Text columns were standardized.
- Date values were converted into proper datetime format.

### 5. Data Type Correction
- Date columns were converted to datetime.
- Numerical columns were converted to appropriate numeric types.
- Text columns were standardized.

### 6. Outlier Detection
The Interquartile Range (IQR) method was used to identify outliers in numerical columns.

Extreme numerical values were capped using the IQR limits instead of deleting complete rows.

## Before vs After Analysis
A comparison table was created to evaluate:
- Row count
- Column count
- Missing values
- Duplicate rows

## Output
The cleaned dataset was saved as:

`retail_store_sales_cleaned.csv`

## Conclusion
The messy retail sales dataset was successfully cleaned and transformed into an analysis-ready dataset. The process improved data consistency, handled missing values and duplicates, corrected data types, and treated extreme numerical values.