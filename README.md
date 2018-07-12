# Kaggle-Home-Credit-Competition
Kaggle Home Credit Default Risk Competition


The goal of this competition is to distinguish those bad customers who may have difficulty in repayment of their new loan if their application is accepted from those good customers who can repay on time. The competition provides severe datasets including 

    1) the application data which is the main training data.
    2) the previous application of the applicants in Home Credit 
    3) Other credit lines of the applicants in other financial institution
    4) Credit Card Information 
    5) Repayment History
    
  
Processes:

    1) Create Features from datasets (1) to (5), like worst delinquent status, repayment pattern, application details and etc.
    2) Check the values and disribution of features created.'
    3) Xgboost Modeling - Tuning hyper-parameters.
    4) Make Predictions
    
Results:

    1) To act as a brenchmark, first submission used the proportion of default in training set as baseline prediction. Get AUC of 0.5.
    2) Then use newly created features and fit in XGBM. Get AUC of 0.742.


    
    
   
