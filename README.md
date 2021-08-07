## INSURANCE-FRAUD-DETECTION
In this module we detect the amount of fraud in insurance claims by the features by looking at different models such as XGBoost, random forest and others.

## Steps involved

1) First we look at different variables and drop the variables we find to be unnecessary.

2) Then we see the categorical variables with missing values and handle the ordinal categorical variables which are variables that can be ranked and assign them with different values that are numerical . Finally we drop the variables we do not need.

3) Since the data is imbalanced as the number of people committing fraud are way less than those who do not . So we use the oversampling technique to make number of people commiting fraud to be equal to those who do not by using SMOTE technique.

4) Now we test different models to check which is more accurate to find that random forest and xgboost are the best methods we can use.

5) We tune the parameters of xgboost and random forest by hyperparameter tuning to arrive at the best model.







