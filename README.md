# Customer Churn Analysis

This project analyzes churn for 7,043 telecom customers using the Telco 
Customer Churn dataset. After cleaning the data and encoding features, 
two models — Logistic Regression and Random Forest — were trained to 
predict which customers are likely to churn.

**Key insight:** Billing-related factors (TotalCharges, MonthlyCharges) 
and tenure are the strongest predictors of churn — far more than any 
demographic factor like gender or partner status. Customers with 
shorter tenure and higher charges are the most at-risk segment for 
retention efforts.

**Tools used:** Python, Pandas, scikit-learn, Seaborn, Matplotlib
