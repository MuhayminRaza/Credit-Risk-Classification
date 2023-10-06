# Credit-Risk-Classification

**Overview of the Analysis**

The purpose of the analysis was to train and evaluate a model based on loan risk. The set contained two types of loans: healthy (0) loans and high-risk (1) loans.
Firstly: The data was split into training and tests. The imbalanced data was evaluated and then the oversampled data. This was done by using the Logistic Regression Model with both sets of data and generating BAS, recall and precision scores using the confusion matrix and by geneating the classification report. 

**Results**
Machine Learning Model 1:
Balanced Accuracy Score: 0.99
Precision: 1.00
Recall: 0.99 

Machine Learning Model 2:
Balanced Accuracy Score: 0.99
Precision: 0.85
Recall: 0.92

**Summary**

The Regression model with the OverSampled data performed better than the imbalanced data as the BAS were similar however the oversampled model displayed better precision and recall for higher-risk loans. Based on this, I'd recommend the oversampled model for predicting. (Please see the screenshots of the classification report for the imbalanced and oversmapled data).
