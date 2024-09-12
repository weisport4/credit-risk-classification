# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis and what financial information the data was on, and what you needed to predict.
   Analyzie performance of model for predicting high-risk and healthy loans to be able to better understand loan risk
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
   Loan status is what is being analyzed for prediction
* Describe the stages of the machine learning process you went through as part of this analysis.
    Evaluating data for numerics, data null values, determine whether scaled data is needed based on min/max, review correlations to help understand data
    for what can be predicted, seperate the data into labels and features for model analysis, scale the data, seperate the data into y/x variables for testing and training datasets, fit the model, generate the confusion matrix and classification reports for evaluation, save the prediction data values to a file
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
    Logistic Regression - however, a function was created so that other models can be used to see if other models could be better predictors

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * The Model has a high accuracy of 99% suggesting it performs well in distinguishing healthy and high-risk loans. The model is slightly less precise in identifying high-risk loans. Recall is high for both high-risk and healthy. The F1 Score balances well also at 92%. A nice strong model.
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
  Linear Regression was the only model used in this homework.  Further evaluation can be done using the function.
