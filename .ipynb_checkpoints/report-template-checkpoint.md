# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of the analysis is to create model that will accurately predict loan health and high risk loans.
The data was comprised of debt to income , derogatory marks, and borrower income to help the predictions.
The counts that are being predicts are counts of the data frame label, they indicate loan status.
In this analysis Logistic Regression was used as part of the Analysis and Over sampling.
The logistic regresion method turns data into 1's and 0's to attempt to predict an outcome. Resampling reffers to running the the model
with large or small data sets.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

Machine Learning Model 1:
    
                  precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384

Machine Learning Model 2: Slight improvement loan success (1)
                  precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619

    accuracy                           0.99     19384
   macro avg       0.92      0.99      0.95     19384
weighted avg       0.99      0.99      0.99     19384



## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
The Logistic Regression with Random Over sampling works best because the accuraccy score was near perfect.
Performance does depend on the problem being solved, in this case the rpoblem was binary loan status.

If you do not recommend any of the models, please justify your reasoning.
I would recommend the use of Logistic regression with Random Over sampling for problems with a simple black & white answer.