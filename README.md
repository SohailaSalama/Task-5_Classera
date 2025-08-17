# Task-5_Classera
Sales data analysis notebook exploring trends, cleaning data, and visualizing product performance using Python (Pandas, Seaborn).
# Sales Data Analysis Notebook

🔍 A step-by-step exploration of sales transaction data to uncover business insights and patterns.

## What This Notebook Does

This Jupyter notebook performs a complete analysis of sales data, walking through:

1. **Data Loading & First Look**
   - Imports the dataset (2,823 sales records)
   - Examines structure, data types, and basic statistics

2. **Data Cleaning**
   - Fixes missing values in addresses and locations
   - Checks for negative values in key metrics
   - Validates sales calculations (quantity × price)

3. **Feature Engineering**
   - Extracts time components from dates (year, month, day, weekday)
   - Calculates profit margins and total costs
   - Identifies holiday season orders (Nov-Dec)

4. **Customer Analysis**
   - Tracks days between customer orders
   - Calculates order frequency per customer

5. **Visualizations**
   - Product line performance comparison
   - Time-based sales trends (ready for deeper analysis)

## Key Questions Answered

✔ Which product lines generate the most revenue?  
✔ When do most sales occur (by month/weekday)?  
✔ How accurate are the existing sales records?  
✔ What's the distribution of order sizes and profit margins?

## How To Use

1. **Requirements**: Python 3.8+, Jupyter Notebook
2. **Install dependencies**:
   ```bash
   pip install pandas numpy seaborn matplotlib

