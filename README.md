# Credit_Risk_Resampling

## Overview of the Analysis

Without utilizing a bank, investors can lend money to others using peer-to-peer lending networks. However, as investors are constantly striving to lower risk, you will develop and assess a number of machine-learning models to forecast credit risk using cost-free data provided by the peer-to-peer lending services. In the dataset are loans with a high probability of default.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

The values for the healthy loans (class 0) are nearly the same in the original and the resampled data-based logistic regression models. The precision value of the model (0.95) and the original data are almost comparable for one class (high-risk loans) (0.95). Based on the Logistic Regression Model built with oversampled data, both healthy (0) and high risk (1) loans were identified with a 95% Geometric Mean, suggesting effective classification. For safe loans, the accuracy is 100%, but for high-risk loans, it is just 85%. (a little low). Recall allowed us to catch 91% of high risk loans and 99% of healthy loans.  The F1 score for healthy loans is 100%. But high risk loans have an 88% F1 score, which is relatively low.  Overall, the predictions for the loan data across both classes were substantially more accurate when using the logistic regression model with the resampled data.