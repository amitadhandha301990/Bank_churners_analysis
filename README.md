
Customer Churn Prediction Model
Problem Statement
Customer churn or customer attrition refers to the tendency of clients or customers to abandon a brand and cease being a paying client. The churn rate is the percentage of customers who discontinue using a company's services or products within a specified period. A high churn rate can lead to significant financial losses and damage to the company's reputation.
ABC BANK aims to predict customer churn rates to mitigate potential losses. This project involves creating a machine learning model using various approaches to predict customer churn.
Dataset Description
The dataset is publicly available and contains 10,000 rows with 14 columns. The target variable is Exited, which indicates whether a customer left the bank or not.
Dataset Format
No table of figures entries found.

Variable	
Definition
RowNumber	Unique Row Number
CustomerId	Unique Customer ID
Surname	Surname of the customer
CreditScore	Credit Score of each customer
Geography	Geographical location of customers
City_Category	Category of the city (A, B, C)
Gender	Gender of the customers
Age	Age of each customer
Tenure	Number of years the customer has been with the bank
Balance	Current balance of customers
NumOfProducts	Number of products the customer has
HasCrCard	Whether the customer has a credit card or not
IsActiveMember	Whether the customer is active or not
EstimatedSalary	Estimated salary of each customer
Exited	Customer left the bank or not (Target Variable)
	

Working Flow
1.	Data Splitting: Divide the dataset into training (70%) and testing (30%) sets.
2.	Feature Engineering: Perform necessary feature engineering to prepare the data for model training.
3.	Model Training: Train various machine learning models to predict customer churn.
4.	Accuracy Evaluation: Check the accuracy score for both the training and test sets.
5.	Overfitting Check: Compare the accuracies for training and test sets to assess potential overfitting issues.
Machine Learning Approaches
•	Logistic Regression
•	Decision Trees
•	Random Forest
•	Gradient Boosting
•	Support Vector Machines (SVM)
•	Neural Networks
Results and Evaluation
The performance of different models will be evaluated based on accuracy, precision, recall, F1 score, and ROC-AUC score.

