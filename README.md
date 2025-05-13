# Customer Retention Analysis

##  Project Overview
This project explores the factors that encourage customers to stay with a company over time. By analyzing customer behavior, service details, and contract information, we aim to understand what keeps customers loyal. The insights from this analysis can help businesses improve retention strategies and build long-term customer relationships.

##  Objective
To identify the key reasons customers remain with the company, using data cleaning, outlier detection, and exploratory data analysis (EDA).

##  Dataset
The dataset used is `Customer Churn.csv`, which includes columns like customerID, gender, SeniorCitizen, Partner, Dependents, tenure, PhoneService, MultipleLines, InternetService, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies, Contract, PaperlessBilling, PaymentMethod, MonthlyCharges, TotalCharges, Churn

##  Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

##  Data Cleaning
- Converted string-type numerical fields to numeric values
- Replaced blanks and handled missing data
- Detected and removed outliers from numerical columns. 

##  Analysis Performed
- Visualized relationships between key features and customer retention
- Explored the impact of contract type, tenure,senior citizen and gender on customer loyalty
- Identified patterns showing that customers on longer contracts, with lower monthly charges and longer tenure, are more likely to stay

##  Key Insights
- 5174 customers stayed while 1869 churned out
- Long-term contracts significantly reduce churn
- Gender has no impact on customer retention
- Senior Citizens are more likely to stay longer
- The majority of customers who stayed tend to have services like PhoneService, InternetService (Particularily DSL) and OnlineSecurity enabled.
- Customers are likely to stay when they are paying through Mailed check, Bank Transfer and Credit cards.
- Customers are likely to churn when they payment method is Electronic Check.

##  Conclusion and Recommendations
This analysis provides actionable insights that can help design better customer retention strategies.
- Promote Long-Term Contracts:
    - Offer incentives for customers to commit longer contracts to reduce churn.
- Address Payment Method Concerns:
    - Implement campaigns encouraging customers to switch from electronic checks to more reliable payment methods.
- Customer Engagement in Early Tenure:
    - Focus on improving customers experience within the first year, as churn is highest in this period.
- Special Senior Citizen Retention Programs:
    - Create personalized offers or assistance programs to retain the senir citizens.

##  Project Status
 Completed – Ready for review and further model development. 

