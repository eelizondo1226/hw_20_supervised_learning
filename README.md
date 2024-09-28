# hw_20_supervised_learning

## Overview of the Analysis

The purpose of this assignment was to determine the classifiactions between a heakthy loans and high-risk loans. The data contained the size of the loans, intertest rates in them, the borrower's income, debt to income, number of accounts, derogatory makes, total debt, and loan status. In this analysis we were attempting to predict to the loan status in the data and using the logistic regression model by using the training data. 

## Results

- Accuracy: Recived a 0.99
- Precision: Was 1.00 for Class 0 and 0.84 for Class 1
- Recall: Was 0.99 for Class 0 and 0.94 for Class 1



                precision   recall   f1-score  support

           0       1.00      0.99      1.00     18765
           1       0.84      0.94      0.89       619

    accuracy                           0.99     19384
   macro avg       0.92      0.97      0.94     19384
weighted avg       0.99      0.99      0.99     19384



## Summary


The class that performed the best was the healthy loan (0). It had the higher precision and higher recall between the two. For the purpose for this analysis it's more importnant to be able to predict the healthy loans