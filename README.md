# Credit_Fraud
# Data preprocessing (Numpy, Pandas); Data Visualization (Matplotlib, Seaborn); Classification (sklearn); Finance; Banking

Credit Fraud || Dealing with Imbalanced Datasets

Problem Description
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

Input Dataset
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Outline:
I. Understanding our data
  - cheking missing values, number of transactions (Fraud vs Non-Fraud)

II. Preprocessing
  - Scaling input feature, managing imbalance datasets, random undersampling, splitting data
  - Testing correlation, feature selection, outlier detection and removal

III. Fitting supervised machine learning model
  - Logistic regression
  - Decision Tree Classifier
  - K Neighbouring Classifier
  
IV. Model validation
  - Model accuracy, confusion matrix
  - Model selection
