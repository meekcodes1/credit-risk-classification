# credit-risk-classification

-----
Credit Risk Analysis Report:
-----
## Overview of the Analysis
- In this activity, we are analyzing lending activity data from a lender in order to classify borrowers as either 0 (healthy) or 1 (high risk of defaulting).

## Results
Model 1
- Balance Accuracy Score = 0.952. This score is the Sensitivity + Specificity / 2. In other words, the average of the true positive and true negative results. A score of 0.952 represents an accurate model.
- Precision = [0: 1.00], [1: 0.85]. These scores refer to the true positives divided by positive predictions, and the true negatives divided by negative predictions
- Recall = [0: 0.99], [1: 0.91]. These scores answer the question, what percent of positives/negatives were identified correctly.

Model 2
- Balance Accuracy Score = 0.994. This score is the Sensitivity + Specificity / 2. In other words, the average of the true positive and true negative results. A score of 0.994 represents an accurate model.
- Precision = [0: 1.00], [1: 0.99]. These scores refer to the true positives divided by positive predictions, and the true negatives divided by negative predictions
- Recall = [0: 0.84], [1: 0.99]. These scores answer the question, what percent of positives/negatives were identified correctly.

## Summary
- The following model could be useful to use for the lending company. The model is very accurate at identifying 0 (healthy) borrowers. It is less accurate at identifying 1(unhealthy) borrowers. This is a potential risk that should be acknowledged for any user of the model. The oversampled model does perform more accurately and should be considered for use over the original model. It has, however, a lower recall score. This means that fewer healthy borrowers were identified correctly.
