Use churn dataset
**Can you develop a machine learning model that can predict the customers who will leave the company?**
- The aim is to estimate whether a bank's customers leave the bank (churn) or not.
  Dataset overview:
- It consists of 10000 observations and 12 variables.
- Independent variables contain information about customers.
- Dependent variable refers to customer abandonment.

Features:
- Surname: Surname
- CreditScore: Credit score
- Geography: Country (Germany/ France/ Spain)
- Gender: Gender (Female/Male)
- Age: Age
- Tenure: How many years of customer
- Balance: Balance
- NumOfProducts: The number of bank products used
- HasCrCard: Credit card status (0 = No, 1 = Yes)
- IsActiveMember: Active membership status (0 = No, 1 = Yes)
- EstimatedSalary: Estimated salary
- Exited: Churn or not? (0 = No, 1 = Yes)

Instructions:
- Perform data exploration. What insights did you get?
- Perform data cleaning and preprocessing as you deem necessary for this dataset.
- Define the appropriate metric for this dataset case. Explain why you chose this metric.
- Do modeling using decision tree, random forest, adaboost, gradientboost, xgboost models.
- Choose the best 2 models and perform hyperparameter tuning.
- Compare the results before and after tuning. Which model has the most optimal performance?