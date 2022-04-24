# Credit_Risk_Analysis

## Overview
In this challenge we are using different sampling methods to test a machine learning model for credit risk.

## Results

### Naive Random Oversampling
- Balanced Accuracy Score: 0.66
- Precision: 0.011
- Recall: 0.70

### SMOTE Oversampling
- Balanced Accuracy Score: 0.63
- Precision: 0.011
- Recall: 0.57

### Undersampling
- Balanced Accuracy Score: 0.54
- Precision: 0.0067
- Recall: 0.68

### Combination Sampling
- Balanced Accuracy Score: 0.64
- Precision: 0.0097
- Recall: 0.70

### Balanced Random Forest CLassifier
- Balanced Accuracy Score: 1.0
- Precision: 0.90
- Recall: 1.0

### AdaBoost Classifier
- Balanced Accuracy Score: 1.0
- Precision: 0.90
- Recall: 1.0

## Summary
We used 6 different sampling techniques to assess a machine learning model for predicting credit risk. The ensemble methods showed overfitting so they should not be used. Of the four resampling methods, there isn't a standout model to use in predicting credit risk. We should care more about recall when assessing this model.The highest recall is still only 0.70 which leaves room for incorrectly predicting credit risk. 