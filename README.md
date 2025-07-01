# Credit-Card-Default-Analysis
Model to predict whether customer default on loan or not
The purpose of this project is to conduct quantitative analysis on credit card default risk by using 3 machine learning models with accessible customer data, instead of credit score or credit history, with the goal of assisting and speeding up the human decision making process.

## Attribute Information
Below there are the description of the attributes that will be used in our model for better understanding of the data:

**LIMIT_BAL**: Amount of the given credit (NT dollar). It includes both the individual consumer credit and his/her family (supplementary) credit.
**SEX**: Gender (1 = male; 2 = female).
**EDUCATION**: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).
**MARRIAGE**: Marital status (1 = married; 2 = single; 3 = others).
**AGE**: Age (year).
**PAY_1**: the repayment status in September, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
**PAY_2**: the repayment status in August, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
**PAY_3**: the repayment status in July, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
**PAY_4**: the repayment status in June, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
**PAY_5**: the repayment status in May, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
**PAY_6**: the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
**BILL_AMT1**: Amount of bill statement (NT dollar). Amount of bill statement in September, 2005.
**BILL_AMT2**: Amount of bill statement (NT dollar). Amount of bill statement in August, 2005.
**BILL_AMT3**: Amount of bill statement (NT dollar). Amount of bill statement in July, 2005.
**BILL_AMT4**: Amount of bill statement (NT dollar). Amount of bill statement in June, 2005.
**BILL_AMT5**: Amount of bill statement (NT dollar). Amount of bill statement in May, 2005.
**BILL_AMT6**: Amount of bill statement (NT dollar). Amount of bill statement in April, 2005.
**PAY_AMT1**: Amount of previous payment (NT dollar). Amount paid in September, 2005.
**PAY_AMT2**: Amount of previous payment (NT dollar). Amount paid in August, 2005.
**PAY_AMT3**: Amount of previous payment (NT dollar). Amount paid in July, 2005.
**PAY_AMT4**: Amount of previous payment (NT dollar). Amount paid in June, 2005.
**PAY_AMT5**: Amount of previous payment (NT dollar). Amount paid in May, 2005.
**PAY_AMT6**: Amount of previous payment (NT dollar). Amount paid in June, 2005.
**default**: Default payment next month.(Yes = 1, No = 0)

# Project Overview
In this project, I performed
Explorative Data Analysis, to bring out relationship between features , correlations between features,
encoding categorical features, identifying missing values , duplicates.
Establish relatiion between Default and features.

# Build Machine Learning models: 
Logistic Regression X GridSearchCV
Random Forest X RandomSearchCV
lightgbm X Optuna 


# Evaluation Metrics:
f1-score , roc_auc_score


