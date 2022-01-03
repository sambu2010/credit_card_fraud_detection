# Credit Card Fraud Prediction

The goal of this project is to develop a model to predict credit card fraud.

To start exploring this goal I used Random Forest algorithm with all the features available and created a model. 

Initial scores are 1.0 and 0.9996137776061234 for training and test data respectively

Confusion matrix is the following:

 [[85299     8]
 
 [   25   111]]

 Precision score is 0.9328 and Recall: 0.8162

 ROC curve looks like this:

 ![roc_auc](https://github.com/sambu2010/credit_card_fraud_detection/blob/main/roc_auc.png)

 For the future of this project I want to explore another classification algorithms to see if they can get me a better score. Also data is highly imbalanced, so resampling of the data is required in order to make the correct predictions