# Retail Sales Exploratory Data Analysis

## Objective

The objective of this project is to perform Exploratory Data Analysis (EDA) on retail sales data to identify sales trends, customer behaviour patterns, and useful business insights.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The dataset contains **1,000 retail transactions** covering the period from **January 2023 to January 2024**.

The dataset includes information about:
- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

## Analysis Performed

- Dataset shape and column inspection
- Data type analysis
- Missing value analysis
- Descriptive statistics
- Mean, median, mode and standard deviation
- Monthly sales trend analysis
- Quarterly sales trend analysis
- Customer age-group analysis
- Gender distribution analysis
- Revenue by product category
- Correlation analysis using a heatmap
- Age vs Total Amount analysis
- Duplicate record checking

## Key Insights

- The dataset contains **1,000 transactions**.
- The **46–55 age group** has the highest representation with **229 customers**.
- Female customers account for **510 transactions**, while male customers account for **490**.
- **Electronics** generated the highest revenue at **156,905**, followed by Clothing at **155,580** and Beauty at **143,515**.
- **May 2023** recorded the highest monthly sales with revenue of **53,150**.
- **Q4 2023** was the highest-performing quarter with revenue of **126,190**.
- Price per Unit has the strongest positive correlation with Total Amount (**0.852**), while Quantity has a moderate positive correlation (**0.374**).
- Age has a very weak negative correlation with Total Amount (**-0.061**), suggesting no strong linear relationship between age and spending in this dataset.

## Business Recommendations

1. **Prioritize Electronics:** Electronics generated the highest revenue, so inventory availability and promotional campaigns for this category should be prioritized.

2. **Target the 46–55 Age Group:** Since the 46–55 group has the highest customer representation, targeted offers and marketing campaigns can be designed for this segment.

3. **Plan Around High-Sales Periods:** May and Q4 showed strong sales performance. Inventory and promotional campaigns can be planned in advance for similar high-demand periods.

4. **Focus on Product Pricing and Quantity:** Since Total Amount has a strong relationship with Price per Unit and a moderate relationship with Quantity, pricing strategies and quantity-based promotions can be explored to improve revenue.

## Dataset Limitation

The dataset contains **Product Category** information but does not provide individual product names. Therefore, an individual **Top 10 Best-Selling Products** analysis could not be performed.

## Conclusion

This EDA provides a clear overview of retail sales performance, customer demographics, product category revenue, seasonal sales patterns, and relationships between numerical variables. The findings can help businesses improve customer targeting, inventory planning, promotional strategies, and revenue optimization.

## Project File

`Retail_Sales_EDA.ipynb`