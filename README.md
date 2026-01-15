📌 Project Overview

This project focuses on analyzing customer churn and retention patterns in a subscription-based business.
The goal is to identify why customers leave, when they leave, and which factors influence churn, and to provide actionable business recommendations to improve customer retention.

🧰 Tools & Technologies Used

Python

Pandas – data manipulation and analysis

Matplotlib & Seaborn – data visualization

Jupyter Notebook / VS Code

📂 Dataset

Dataset: Telco Customer Churn Dataset

Description:
Contains customer-level information including demographics, services subscribed, contract details, payment methods, monthly charges, tenure, and churn status.

Key Columns:

tenure – Number of months the customer has stayed

MonthlyCharges – Monthly billing amount

TotalCharges – Total lifetime charges

Contract – Contract type

PaymentMethod – Mode of payment

Churn – Whether the customer left the company

📈 Key Analysis Performed
1️⃣ Churn Rate Analysis

Calculated overall churn rate

Identified that approximately 26.5% of customers churned

Insight:
The business faces a significant retention challenge, with roughly one in four customers leaving.

2️⃣ Tenure vs Churn Analysis

Compared average tenure for churned vs retained customers

Churned customers stayed for ~18 months on average

Retained customers stayed for ~38 months on average

Insight:
Churn primarily occurs early in the customer lifecycle, highlighting the importance of early-stage customer experience.

3️⃣ Contract Type vs Churn

Analyzed churn rate across different contract types

Key Finding:

Month-to-month contracts have the highest churn

Long-term contracts (1-year, 2-year) significantly reduce churn

Insight:
Contract commitment is one of the strongest drivers of customer retention.

4️⃣ Monthly Charges vs Churn

Compared average monthly charges for churned vs retained customers

Insight:
Customers who churn tend to have higher monthly charges, suggesting price sensitivity and perceived value issues.

5️⃣ Payment Method vs Churn

Calculated churn rate by payment method

Key Finding:

Customers using Electronic Check show the highest churn

Automatic payment methods have lower churn

Insight:
Payment convenience and automation positively influence retention.

6️⃣ Cohort-Based Retention Analysis (Advanced)

Performed tenure-based cohort analysis to study retention behavior

Retention improves significantly after the first year

Insight:
Customers who remain beyond the first year are far more likely to stay long-term.

💡 Business Recommendations

Improve onboarding and engagement during the first 6–12 months

Encourage customers to shift from month-to-month to long-term contracts

Promote automatic payment methods

Re-evaluate pricing strategies for high monthly charge segments

📁 Repository Structure
FUTURE_DS_02/
│── data/
│   └── telco_churn.csv
│── analysis/
│   └── churn_analysis.ipynb
│── README.md

✅ Conclusion

This project demonstrates a comprehensive customer churn analysis workflow, combining data cleaning, exploratory analysis, visualization, and business reasoning.
The insights derived can directly support data-driven retention strategies and business decision-making.