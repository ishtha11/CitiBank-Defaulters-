# CitiBank-Defaulters-
The objective of this Dataset is that We have to find whether the target variable is the defaulter or not.
The evaluation metric is the accuracy.

File Description(All Copyrights to Kaggle and CitiBank)

X1 - Y: Client's behavior (target); Y=0 then not default, Y=1 then default.
X1 - Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.
X2 -Gender (1 = male; 2 = female).
X3 - Education (1 = graduate school; 2 = university; 3 = high school; 0,4,5,6 = others).
X4 - Marital status (1 = married; 2 = single; 3 = divorce; 0=others).
X5 - Age (year).
X6-X11 - History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows: X6 = the repayment status in September, 2005; X7 = the repayment status in August, 2005; . . .;X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -2 = No consumption; -1 = pay duly; ; 0: The use of revolving credit; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above
X12-X17 - Amount of bill statement (NT dollar). X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005; . . .; X17 = amount of bill statement in April, 2005.
X18-X23 - Amount of previous payment (NT dollar). X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .;X23 = amount paid in April, 2005.

Inference from this dataset:
After importing important libraries and csv file, we did Data Preprocessing (EDA), then there comes modelling. We applied most of the models ike Logistic Regression, Decision Tree Model, Random Forest Model, Bagging Model, Gradient Boosting Model and lastly we applied voting classifier to predict the accuracy.
The final accuracy comes out to be 81%
