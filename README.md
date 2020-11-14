# AllState_Claim_Severity

## Problem Statement:
    a. Predict cost of an insurance claim and thus determine its severity based on claimed cost.

    b. Since we are predicting repair cost (loss) which is of numeric type so we can pose this problem as ‘Regression’ problem
    
## Real world/Business Objectives and Constraints
    a. The cost of a mis-prediction can be quite high.

    b. No strict latency concerns.

    c. Interpretability is partially important.
    
## Type of Machine Leaning Problem

     Target variable is numeric real value so it's regression problem. It is also a Supervised Machine learning problem as we target values for train data
     
## Data Overview:
     a.  Two files are given namely train.csv and test.csv
            Train.csv: the training set. Size: 66.78 MB
            Test.csv - the test set. You must predict the loss value for the ids in this file. Size: 43.6 MB
            
    b. The train dataset has 130 features - 116 are categorical, and 14 are real-valued features. There is a loss associated with each training example. There are 188,318 training       examples
    
    c. The test dataset has same feature sets but no ‘loss’ (dependent variable).We have to predict loss in test set
    
    Link for dataset : https://www.kaggle.com/c/allstate-claims-severity/data

## Performance Metric :

    MAE (Mean Absolute Error)
    
## Solution :

     1. First we did EDA and Feature Engineering on train and test data set which is shown in EDA.ipynb and train_test_preparation.ipynb notebook
     2. Modeling shown in modeling.ipynb
     3. Final pipeline shows in Final1.ipynb
