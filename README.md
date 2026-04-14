# Healthcare Data Analysis with Python

## Overview

End-to-end analysis of healthcare claims data using Python to identify cost drivers, demographic trends, and the impact of chronic conditions on healthcare spending.

## Tools Used

- Python (pandas for data analysis, matplotlib for visualization)
- Jupyter Notebook

## Project Overview

This analysis explores how patient demographics and chronic conditions influence healthcare reimbursement patterns.

Key steps included:
- Data cleaning and preprocessing  
- Feature engineering (age calculation from DOB)  
- Outlier handling  
- Creation of a total reimbursement metric (combining inpatient and outpatient costs)
- Aggregation and grouping using pandas (groupby operations)
- Data visualization  
- Insight generation  

## Visualization Examples

### Age-Based Cost Analysis
![Age Analysis](age_analysis.png)

### Diabetes Cost Analysis
![Diabetes Analysis](diabetes_analysis.png)

## Key Insights

### Age-Based Trends
- Reimbursement was lowest for beneficiaries under 50  
- Highest average costs were observed in the 50–75 age range  
- Costs did not increase consistently across all age groups, suggesting additional influencing factors beyond age  

### Chronic Condition Impact (Diabetes)
- Beneficiaries with diabetes had significantly higher average reimbursement compared to those without diabetes  
- Average reimbursement for beneficiaries with diabetes was more than double that of those without diabetes, highlighting a substantial cost differential
- Chronic conditions are a major driver of healthcare costs in this dataset  

## Project Structure

- `healthcare_analysis.ipynb` → Full analysis, code, and visualizations

## Data Source

This project uses a publicly available healthcare claims dataset commonly used for fraud detection and cost analysis. The data includes patient demographics, chronic condition indicators, and reimbursement information.

## How to Run

1. Open the notebook in Jupyter Notebook or JupyterLab  
2. Run all cells sequentially  
3. Review visualizations and insights  

## Key Skills Demonstrated

- Data cleaning and preprocessing  
- Feature engineering  
- Exploratory data analysis (EDA)  
- Data aggregation and grouping  
- Data visualization  
- Translating data into actionable insights  

---

## Author

KatCodes7
