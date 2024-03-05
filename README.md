# credit-risk-classification-report

## Overview of the Analysis

We did an analysis on this dataset to attempt to train a machine learning model to accurately predict which loans were healthy and which are at a high risk of default. The analysis used loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, and total debt in order to attempt to predict the health of the loan. High risk loans were coded as "1" while seemingly healthy loans were coded as "0". We initially created a supervised logistic regression model that did not use any oversampling, then created a similar supervised model that used oversampling in order to create a more robust sample size for the risky loans.

## Results

* Machine Learning Model 1(no oversampling):
    * balanced accuracy score: 96.7%
    * Healthy loans
        * precision:100%
        * recall:99%
    * High risk loans
        * precision:84%
        * recall:94%


* Machine Learning Model 2(random oversampling):
    * balanced accuracy score: 99.3%
    * Healthy loans
        * precision:100%
        * recall:99%
    * High risk loans
        * precision:84%
        * recall:99%

## Summary

The second model appears to be more accurate when trying to predict high risk loans. Though the precision score is still not exceptional at 84%, the balanced accuracy score of 99.3% makes me feel that it would be reasonable to recommend this model to use for some further testing with predicting high risk loans.