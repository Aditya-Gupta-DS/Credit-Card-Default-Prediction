# Credit-Card-Default-Prediction

# Problem Statement
This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. We can use the K-S chart to evaluate which customers will default on their credit card payments.
Objective of our project is to predict which customer might default in upcoming months

# Data Description
This research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. This study reviewed the literature and used the following 23 variables as explanatory variables:

X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.
X2: Gender (1 = male; 2 = female).
X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).
X4: Marital status (1 = married; 2 = single; 3 = others).
X5: Age (year).
X6 - X11: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows: X6 = the repayment status in September, 2005; X7 = the repayment status in August, 2005; . . .;X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
X12-X17: Amount of bill statement (NT dollar). X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005; . . .; X17 = amount of bill statement in April, 2005.
X18-X23: Amount of previous payment (NT dollar). X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .;X23 = amount paid in April, 2005.

# When does default happen?
Credit card default happens when you have become severely delinquent on your credit card payments.Missing credit card payments once or twice does not count as a default. A payment default occurs when you fail to pay the Minimum Amount Due on the credit card for a few consecutive months

# Patterns/Trends in the Data

## Defaulters as per Gender
![image](https://user-images.githubusercontent.com/47490381/121402145-2d1b7f00-c977-11eb-8d37-5614f9d31cda.png)

## Defaulters as per Education
![image](https://user-images.githubusercontent.com/47490381/121402236-4290a900-c977-11eb-8202-ea6d5aab7152.png)

## Defaulters as per Marital Status
![image](https://user-images.githubusercontent.com/47490381/121402302-563c0f80-c977-11eb-86d3-f82e4d3710dd.png)

## Number of users as per Age (21-79)
![image](https://user-images.githubusercontent.com/47490381/121402521-9dc29b80-c977-11eb-879e-a0bc8c350ba8.png)

# Model Evaluation
![image](https://user-images.githubusercontent.com/47490381/121402800-ed08cc00-c977-11eb-9d13-37c092feac2d.png)
![image](https://user-images.githubusercontent.com/47490381/121402850-fabe5180-c977-11eb-8e59-900edeafe738.png)

# Conclusion
Out of different models used for this problem, Random Forest performed best compared to other models with ROCAUC score as 0.911 and f1 score as 0.83








