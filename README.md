# credit-risk-classification
Module 20 Challenge

## Overview of the Analysis

I was asked to build a model that can identify the creditworthiness of borrowers using a dataset of historical lending activity from a peer-to-peer lending services company. In the analysis, I was asked to predict loan_status. A value of 0 for loan_status means the loan is healthy, while a value of 1 means the loan has a high risk of defaulting.

In completing the analysis, I broke the data into labels, loan_status, and features, all data other than loan_status. Then, from those datasets, I created training and testing datasets. After breaking up the dataset, I took the training datasets and used LogisticRegression to create a model to correctly predict the labels based on the features provided. Next, I applied the model to the testing datasets and used the features to predict the labels for the testing dataset. Finally, I created a confusion matrix and classification report to determine how well the model correctly predicts the labels for the testing dataset.

## Results

### Confusion Matrix
![confusion_matrix.png](https://github.com/rollernathan/credit-risk-classification/blob/main/Credit_Risk/images/confusion_matrix.png)

### Classification Report
![classification_report.png](https://github.com/rollernathan/credit-risk-classification/blob/main/Credit_Risk/images/classification_report.png)

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
