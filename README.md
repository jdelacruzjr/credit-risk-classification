# Credit Risk Classification - Training, Evaluating a Model to Indentify Credit Worthiness

![loan_signing](Images/loan_signing.jpg)
# Logistic Regression Model Analysis:

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this challenge was to test 2 Machine Learning Models and determine whether the models are reliable predictors of healthy loans and high risk loans.
* The data used for analysis consisted of a borrower's credit worthiness information such as debt to income (DTI) ratios, late payments, interest rates, total loan amounts, etc..
* The data was split into training and test data to make predictions.
* Using the labels from the `loan_status` column, which indicate whether a loan is `healthy` or `high risk` and the featured data from the remaining columns, we used both `LogisticRegression`, and `LogisticRegressionROS` (or a resampling method) to predict credit worthiness of borrowers.

## Results

The balanced accuracy scores, the precision & recall scores of both machine learning models.

* Machine Learning Model 1 (Logistic Regression Model):
  * Accuracy for healthy loans: 99%
  * Precision for healthy loans: 100%
  * Recall for healthy loans: 99% 
  * Precision for risky loans: 85%
  * Recall for risky loans: 91%

* Machine Learning Model 2 (Logistic Regression Model w/ROS):
  * Accuracy for healthy loans: 99%
  * Precision for healthy loans: 100%
  * Recall for healthy loans: 99% 
  * Precision for risky loans: 84%
  * Recall for risky loans: 99%

## Summary

Although both models experienced an acceptable accuracy score, the LG Model w/ROS achieved a much higher recall score of 99%. Given that the logistic regression model enjoys both higher accuracy and more consistent scoring, I would recommend using this model for the purposes of choosing which loans a bank should approve.

While the performance of these models does depend on the problem we are trying to solve in this case, I believe it is much more appealing for a bank to have selected less healthy loans, than more at risk loans so while we would want to see high scores and consitency all around, in this instance it is of more importance for the models to predict the `1`'s.
 
 ### Notes & References:

  I created this shareable link to my repository <https://github.com/jdelacruzjr/credit-risk-classification.git> and submitted it to <https://bootcampspot-v2.com>
  
### Copyright

Adobe Stock Images © 2023 Adobe. All Rights Reserved.
Trilogy Education Services © 2023. All Rights Reserved.