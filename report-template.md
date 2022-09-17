# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of this analysis was to use a Logisitic Regression model to predict whether a loan was healthy (0) or high-risk (1). The pre-existing data that was provided had a far greater number of healthy loans than high risk loans, so two different models were constructed in order to determine which model was better: one based of a balanced data set or one based of an imbalanced data set.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1 (scores are based off the model's ability to predict high risk loans):
Accuracy: 95%
Precision: 85%
Recall: 91%


* Machine Learning Model 2 (scores are based off the model's ability to predict high risk loans):
Accuracy: 99%
Precision: 84%
Recall: 99%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

I would recommend that the second model (based off an oversampled data set) be used, as it had higher accuracy and recall than the first model (based of the original data set). The second model also had a higher f1 score, which is one of the most important evaluation metrics in machine learning.