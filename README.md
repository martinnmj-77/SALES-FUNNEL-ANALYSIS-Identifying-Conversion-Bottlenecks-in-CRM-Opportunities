# Sales Funnel Analysis: Identifying Conversion Bottlenecks in CRM Opportunities

## Overview
This project analyzes a CRM sales opportunities dataset to identify bottlenecks in the sales funnel, measure conversion rates across deal stages, and evaluate factors affecting pipeline performance.

Using Python for data cleaning, feature engineering, and exploratory data analysis, the project uncovers patterns in deal progression, sales cycle duration, product performance, and opportunity outcomes.

---

## Objective
The aim of this project is to:

- Analyze conversion rates across sales funnel stages  
- Identify stages where opportunities drop off  
- Detect bottlenecks in the sales pipeline  
- Evaluate sales cycle efficiency  
- Assess product and account-level performance  
- Generate insights to improve win rates and pipeline effectiveness  

---

## Dataset
This project uses a CRM Sales Opportunities dataset consisting of four related tables:

### 1. sales_pipeline.csv (Primary Fact Table)
Contains opportunity-level sales records, including:
- Opportunity ID  
- Account  
- Product  
- Deal Stage  
- Sales Agent  
- Engage Date  
- Close Date  
- Close Value  

### 2. accounts.csv
Contains account-level attributes:
- Revenue  
- Number of Employees  
- Office Location  
- Subsidiary Information  

### 3. products.csv
Contains product-level information:
- Product Name  
- Product Performance Data  

### 4. sales_teams.csv
Contains team and sales representative data.

---

## Data Preparation
The analysis includes:

- Handling missing values  
- Merging multiple datasets  
- Removing redundant fields  
- Creating engineered features:
  - Sales Cycle Days  
  - Deal Won Indicator  
  - Deal Size Segments  
  - Filled Close Values  

A merged analytical dataset (`analysis_df`) was created for analysis.

---

## Tools and Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## Analysis Performed

### Sales Funnel Analysis
- Stage-wise opportunity counts  
- Funnel conversion rates  
- Drop-off analysis  
- Bottleneck identification  

### Sales Cycle Analysis
- Average sales cycle duration  
- Sales cycle variation by outcome  
- Cycle length patterns  

### Product Performance Analysis
- Product-level win/loss analysis  
- Revenue distribution by product  
- Product contribution to pipeline  

### Deal Performance Analysis
- Won vs Lost opportunity analysis  
- Deal size segmentation  
- Opportunity value trends  

---

## Key Insights
This project helps identify:

- Stages with the highest opportunity drop-off  
- Sales process bottlenecks  
- Patterns affecting conversions  
- Products linked to stronger outcomes  
- Opportunities to improve pipeline efficiency  

---

## Project Structure

data/
[sales_teams.csv](https://github.com/user-attachments/files/27135583/sales_teams.csv)
[sales_pipeline.csv](https://github.com/user-attachments/files/27135581/sales_pipeline.csv)
[products.csv](https://github.com/user-attachments/files/27135580/products.csv)
[accounts.csv](https://github.com/user-attachments/files/27135579/accounts.csv)

notebooks/
[https://github.com/martinnmj-77/SALES-FUNNEL-ANALYSIS-Identifying-Conversion-Bottlenecks-in-CRM-Opportunities/blob/main/Sales_Funnel_Analysis_Project%20.ipynb)
 
README.md

requirements.txt
```

---

## How to Run
Clone the repository:

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

Open:

```bash
Sales_Funnel_Analysis.ipynb
```

---

## Future Improvements
- Sales rep performance analysis using sales_teams data  
- Predictive modeling for deal conversion  
- Interactive dashboard in Power BI or Tableau  
- Funnel forecasting and pipeline risk analysis  

---

## Author
Martin J. Mathew

Data Analytics Portfolio Project
