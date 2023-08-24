# Credit Risk Classification Challenge
by Andrea Monnerie

## Overview of the Analysis

This project two techniques will be used to predict the creditworthiness of borrowers using dataset of historical lending activity from a lending company. Specifically I will predict rather it is a healthy loan or a high-risk loan. The two methods that were used was the Logistic Regression Model with the original data and with resampled data (using RandomOverSampler). For both methods a balanced_accuracy score, confusion matrix, and a classification report was done. For the resampled data, the distinct values were counted.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Balanced Accuracy: 95.2%
  * Precision:
      * Healthy Loan: 100%
      * High-risk Loan: 85%
  * Recall scores:
      * Healthy Loan: 99%
      * High-risk Loan: 91%  

* Machine Learning Model 2:
  * Balanced Accuracy: 99.3%
  * Precision:
      * Healthy Loan: 100%
      * High-risk Loan: 84%
  * Recall scores:
      * Healthy Loan: 99%
      * High-risk Loan: 99%

## Summary

The first model was okay, but the second model performed the best. Even though the precision is lower by 1% for the high risk loans, the accuracy is significantly higher than the first model.
For this scenarion and the purpose of this analysis, it is best to base the predictions on the high-risk loans since this loans could put the company at risk. Thus, I would recommend the second model becuase it is more accurate
