# Credit Card Fraud Detection

## Abstract

With the growth of e-commerce websites, people and financial companies rely on online services
to carry out their transactions that have led to an exponential increase in the credit card frauds.
Fraudulent credit card transactions lead to a loss of huge amount of money. The goal of this project is to develop an effective fraud detection system to reduce the losses incurred by the customers and financial institutions.

## Design

A good fraud detection system should be able to identify the fraud transaction accurately and should make the detection possible in real-time transactions. The Credit Card Fraud Detection Problem includes modeling past credit card transactions with the knowledge of the ones that turned out to be a fraud. This model is then used to identify whether a new transaction is fraudulent or not. 

## Data

Dataset used for this problem has been acquired from kaggle.com. It includes 1852394 total observations where 1842743 are valid transactions and 9651 are fraudulent.
Dataset includes 23 features, 14 of which are categorical.

## Algorithms

Initial EDA includes handling missing values, categorical variables conversion, type conversion and feature engineering for some of the raw features.

Data is highly imbalanced. To correct this stratified train val test split is made to ensure the proper distribution of target's positive observations between training, validation and test datasets.
SMOTE oversampling technique is used to address the class imbalance.

Modeling is done using 3 different algorithms: logistic regression, random forest and XGBoost.
XGBoost model is selected as the final model. It provides the best performance out of the three.
Final tuning is done after model selection by identifying the best probability threshold that yeilds the most correct results.

## Tools

- numpy and pandas are used for data cleaning and manipulation
- sklearn is used for modeling
- matplotlib and seaborn are used for visualization

## Communication

The jupyter notebook containing the data and analysis and the PowerPoint presentation are located in the GitHub repo folder for this project.
