# customer_churn_minor_project

##  Overview
This project focuses on predicting customer churn using machine learning techniques. Customer churn refers to the phenomenon where customers discontinue their relationship with a service provider. In subscription-driven markets, retaining customers is more cost-effective than acquiring new ones, making churn prediction a critical business priority.

##  Objectives
- Analyze customer data to identify churn drivers  
- Build predictive models for churn classification  
- Evaluate model performance using robust metrics  
- Provide actionable strategies to improve customer retention  

##  Dataset
The dataset includes:  
- **Demographics**: Gender, tenure, age groups  
- **Usage Patterns**: Service interaction frequency, activity decline  
- **Subscription Details**: Contract type, payment method, monthly/total charges  
- **Target Variable**: Churn (Yes/No)  

##  Preprocessing
- Handling missing values (imputation/removal)  
- Encoding categorical variables (One-Hot/Label Encoding)  
- Feature scaling (Standardization/Min-Max Normalization)  

##  Exploratory Data Analysis (EDA)
Key insights:  
- Higher churn among **month-to-month contracts**  
- Customers with **high charges** show increased churn probability  
- Class imbalance observed (majority non-churn vs. minority churn)  

##  Models Used
- Logistic Regression (baseline, interpretable)  
- Decision Tree (non-linear relationships)  
- Random Forest (ensemble, best performance)  

##  Evaluation Metrics
- Accuracy, Precision, Recall, F1-score  
- Confusion Matrix for trade-off analysis  
- Random Forest achieved the **highest accuracy and balanced performance**  

##  Results
- Successfully predicts churn and identifies high-risk customers  
- Provides actionable insights for proactive retention strategies  

##  Recommendations
1. **Targeted Incentives**: Loyalty discounts for high-risk customers  
2. **Proactive Outreach**: Automated check-ins for declining usage patterns  
3. **Subscription Optimization**: Review contract terms and payment friction  

##  Tools & Technologies
- Python  
- Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- Jupyter Notebook  
