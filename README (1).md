# Credit Risk Detection

This repository contains all the code as a part of the project on Credit Card Fraud Detection. The list of input variables include: </br>

ID: ID of each client </br>
LIMIT_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary credit </br>
SEX: Gender (1=male, 2=female) </br>
EDUCATION: (1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown)</br>
MARRIAGE: Marital status (1=married, 2=single, 3=others) </br>
AGE: Age in years </br>
PAY_0: Repayment status in September, 2005 (-1=pay duly, 1=payment delay for one month, 2=payment delay for two months, … 8=payment delay for eight months, 9=payment delay for nine months and above) </br>
PAY_2: Repayment status in August, 2005 (scale same as above) </br>
PAY_3: Repayment status in July, 2005 (scale same as above) </br>
PAY_4: Repayment status in June, 2005 (scale same as above) </br>
PAY_5: Repayment status in May, 2005 (scale same as above) </br>
PAY_6: Repayment status in April, 2005 (scale same as above)</br>
BILL_AMT1: Amount of bill statement in September, 2005 (NT dollar) </br>
BILL_AMT2: Amount of bill statement in August, 2005 (NT dollar) </br>
BILL_AMT3: Amount of bill statement in July, 2005 (NT dollar) </br>
BILL_AMT4: Amount of bill statement in June, 2005 (NT dollar) </br>
BILL_AMT5: Amount of bill statement in May, 2005 (NT dollar) </br>
BILL_AMT6: Amount of bill statement in April, 2005 (NT dollar) </br>
PAY_AMT1: Amount of previous payment in September, 2005 (NT dollar) </br>
PAY_AMT2: Amount of previous payment in August, 2005 (NT dollar) </br>
PAY_AMT3: Amount of previous payment in July, 2005 (NT dollar) </br>
PAY_AMT4: Amount of previous payment in June, 2005 (NT dollar) </br>
PAY_AMT5: Amount of previous payment in May, 2005 (NT dollar) </br>
PAY_AMT6: Amount of previous payment in April, 2005 (NT dollar) </br>
default.payment.next.month: Default payment (1=yes, 0=no) </br> </br>

Roughly, the project can be divided into the following sections: </br>
1. Data Exploration and Validation </br>
2. Data Cleaning </br>
3. Model Building and Validation (Logistic Regression) </br>
4. Handling Class Imbalance </br>
5. Feature Engineering </br>
6. Model Building and Validation (Decison Tree, Random Forest and XGBoost) </br> </br>

## Model Accuracy obtained from the various algorithms: </br> </br>

**1. Logistic Regression:** 78.833 % </br>
**2. Decision Tree :** 75.03 % </br>
**3. Random Forest:** 81.75 % </br>
**4. XGBoost:** 81. 43 %
