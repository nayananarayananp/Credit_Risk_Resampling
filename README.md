# Credit_Risk_Resampling

## Overview of the Analysis

Without utilizing a bank, investors can lend money to others using peer-to-peer lending networks. However, as investors are constantly striving to lower risk, we have to develop and assess a number of machine-learning models to forecast credit risk using the data provided. This loan data is an excellent candidate for supervised learning because we already have the data for both healthy and high risk loans. The advantage of supervised learning is that, when the model has been set, we may use it to forecast fresh data. In other words, we can foretell whether loans will be profitable or not in the future.

We are creating a toolkit of models based on data provided by a peer-to-peer lending organization and using supervised learning techniques to predict if a loan would default. To back up our prediction, we'll do the following:

   * Create Training and Testing Sets for the Data
   * With the original data, creating a logit regression model. 
   * Logistic Regression Model Prediction Using Resampled Training Data

## Results
* Modeling Logistic Regression Using the Original Data:
  * Model accuracy is 95.2%
  * Precision average 99%
  * Recall average 99%
  * F1 score average 100%

* With resampled training data, a logistic regression model:
  * Model accuracy is 95.2%
  * Precision average 99%
  * Recall average 99%
  * F1 score average 100%.

## Summary

The values for the healthy loans (class 0) are nearly the same in the original and the resampled data-based logistic regression models. The precision value of the model (0.95) and the original data are almost comparable for one class (high-risk loans) (0.95). Based on the Logistic Regression Model built with oversampled data, both healthy (0) and high risk (1) loans were identified with a 95% Geometric Mean, suggesting effective classification. For safe loans, the accuracy is 100%, but for high-risk loans, it is just 85%. (a little low). Recall allowed us to catch 91% of high risk loans and 99% of healthy loans.  The F1 score for healthy loans is 100%. But high risk loans have an 88% F1 score, which is relatively low.  Overall, the predictions for the loan data across both classes were substantially more accurate when using the logistic regression model with the resampled data.