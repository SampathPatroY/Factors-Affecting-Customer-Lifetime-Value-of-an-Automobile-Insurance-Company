# Factors-Affecting-Customer-Lifetime-Value-of-an-Automobile-Insurance-Company
Overview
This project develops a predictive model for Customer Lifetime Value (CLV) in the auto insurance sector using linear regression analysis. It incorporates factors such as number of policies, monthly premium, total claim amount, number of open complaints, and marital status to forecast CLV accurately.

Data Source
UCI ML Repository dataset from Kaggle, containing customer information from 5 American states.

Methodology
Data Analysis
Exploratory Data Analysis (EDA) on key variables
Correlation analysis
Visualization of relationships between CLV and predictor variables
Model Development
Linear Regression with log transformations for continuous variables
Testing of key assumptions:
Linearity in parameters
Independence of errors
Homoscedasticity
No perfect multicollinearity
Normality of errors
No endogeneity
Key Findings
Model Performance
R-squared: 0.2556
Adjusted R-squared: 0.2552
F-statistic: Significant (p < 2.2e-16)
Variable Impacts
Monthly Premium Auto: Strong positive relationship with CLV
Number of Open Complaints: Negative impact on CLV
All predictors statistically significant (p < 0.05)
Challenges and Future Work
Limitations
Heteroskedasticity issues identified
Potential omitted variable bias
Future Improvements
Explore advanced techniques:
XGBoost
Random Forest
Neural Networks
Incorporate additional variables (e.g., driving experience, age, education)
Skills Demonstrated
Data Analysis and Visualization
Linear Regression Modeling
Statistical Assumption Testing
Business Insight Generation
Tools Used
R (for statistical analysis)
Jupyter Notebook (for exploratory data analysis)
Kaggle (data source)
