# Customer Churn Analysis

## Project Overview
This project focuses on analyzing customer churn data to identify the key factors that cause customers to leave a service. The goal is to provide data-driven insights and actionable recommendations to reduce churn and improve customer retention.

---

## Problem Statement
Customer churn leads to revenue loss and affects business growth. This project aims to analyze customer behavior and identify patterns that contribute to churn.

---

## Objectives
- Calculate churn rate
- Analyze customer behavior
- Identify factors affecting churn
- Provide business recommendations

---

## Dataset Information
- Dataset Name: customer_churn.csv
- Number of Rows: 500+
- Number of Columns: 4 (may vary)
- Target Variable: churn

---

## Project Structure
project/
│
├── data/
│ ├── raw_data.csv
│ └── cleaned_data.csv
│
├── notebooks/
│ ├── 1_data_cleaning.ipynb
│ ├── 2_eda.ipynb
│ └── 3_analysis.ipynb
│
├── reports/
│ ├── executive_summary.pdf
│ └── technical_report.pdf
│
├── presentation/
│ └── business_presentation.pptx
│
├── capstone_analysis.ipynb
├── README.md
└── requirements.txt

---

## Steps Performed

### 1. Data Cleaning
- Removed missing values
- Removed duplicate records
- Standardized column names
- Encoded categorical variables

### 2. Exploratory Data Analysis (EDA)
- Analyzed churn distribution
- Visualized data using charts and graphs
- Identified patterns and relationships

### 3. Data Analysis
- Calculated churn rate
- Performed correlation analysis
- Conducted group-based comparisons
- Tested hypotheses

### 4. Modeling (Optional)
- Applied Logistic Regression
- Evaluated model performance

---

## Key Findings
- Churn rate is significant
- Customers with low usage are more likely to churn
- Certain features strongly influence churn
- Customer engagement impacts retention

---

## Business Recommendations
- Target low-usage customers with offers
- Improve customer engagement strategies
- Introduce loyalty programs
- Use predictive analytics for early churn detection

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## How to Run the Project

1. Clone the repository
2. Install required libraries:
   pip install -r requirements.txt
3. Open Jupyter Notebook
4. Run notebooks in order:
   - 1_data_cleaning.ipynb
   - 2_eda.ipynb
   - 3_analysis.ipynb

---

## Results
The project successfully identified key factors affecting customer churn and provided actionable insights to reduce churn and improve business performance.

---

## Future Scope
- Use advanced machine learning models
- Add more features for better analysis
- Build real-time prediction system
- Develop dashboard for visualization

---

## Author
Shivam Kumar
