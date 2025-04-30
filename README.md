# Credit-Card-Fraud-Detection
Dataset link = https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Project Overview: This project uses machine learning algorithms to detect fraudulent credit card transactions. The dataset consists of anonymized features from transactions, including transaction amount and time, along with a target variable that indicates whether a transaction is fraudulent or not. 
Techniques Used
Data Preprocessing: 
o Standard scaling of the Amount feature to normalize transaction amounts. 
o Removal of the Time feature as it was deemed irrelevant. 
o Dropping duplicate rows for data quality.
Class Imbalance Handling: 
o Undersampling: Randomly reducing the number of normal transactions to balance the dataset. 
o SMOTE (Synthetic Minority Oversampling Technique): Generating synthetic fraudulent transactions to balance the dataset.
Feature Engineering: 
o Engineered features like transaction frequency and spending patterns to enhance model performance.
Model Selection: 
o Logistic Regression 
o Decision Tree Classifier
Model Evaluation: 
o Used accuracy, precision, recall, and F1-score as evaluation metrics to measure model performance, with a focus on minimizing false positives while achieving high accuracy.
