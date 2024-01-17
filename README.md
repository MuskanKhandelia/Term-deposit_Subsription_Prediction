# Term Deposit Prediction Model

## Problem Statement

The goal of this project is to build a predictive model to determine whether a bank client will subscribe to a term deposit or not. The output variable (y) is binary, representing whether the client has subscribed ("yes") or not ("no").

## Dataset Information

### Input Variables
1. age (numeric)
2. job: type of job (categorical)
3. marital: marital status (categorical)
4. education: level of education (categorical)
5. default: has credit in default? (binary)
6. balance: average yearly balance, in euros (numeric)
7. housing: has housing loan? (binary)
8. loan: has a personal loan? (binary)
9. contact: contact communication type (categorical)
10. day: last contact day of the month (numeric)
11. month: last contact month of the year (categorical)
12. duration: last contact duration, in seconds (numeric)
13. campaign: number of contacts performed during this campaign (numeric)
14. pdays: number of days since the client was last contacted (numeric)
15. previous: number of contacts performed before this campaign (numeric)
16. poutcome: outcome of the previous marketing campaign (categorical)

### Output Variable
17. y: has the client subscribed to a term deposit? (binary)

## Approach

1. **Data Cleaning and Exploration:**
   - Conducted data cleaning and exploration using Pandas and Seaborn.
   - Identified correlations and gained insights from the exploratory data analysis (EDA).

2. **Data Preprocessing:**
   - Handled categorical variables by converting them into numerical format.
   - Utilized label encoding for binary variables and one-hot encoding for other categorical variables.

3. **Model Creation:**
   - Developed a logistic regression model using Scikit-learn.
   - Followed the entire machine learning life cycle, including model training and evaluation.

4. **Model Evaluation:**
   - Evaluated the model using the following metrics:
      - Accuracy Score: 0.91
      - Precision Score: 0.66

## Conclusion

The logistic regression model achieved a high accuracy score of 91%, with insights from EDA providing valuable context.
