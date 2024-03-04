
Credit Risk Analysis Report
Overview of the Analysis
The purpose of this analysis was to develop machine learning models to predict credit risk in lending. The dataset contained various features related to loan applications, with the target variable being the loan status, where 0 represents a healthy loan and 1 represents a high-risk loan.

Results
Model 1:
Precision: 0.85
Recall: 0.91
Accuracy: 0.99
F1-score: 0.88
Model 2:
Precision: 0.84
Recall: 0.99
Accuracy: 0.99
F1-score: 0.91
Summary
Both Model 1 and Model 2 achieved high accuracy scores, with values close to 0.99, indicating strong performance in classifying loans. However, when considering precision and recall, Model 2 outperformed Model 1 in terms of identifying high-risk loans (label 1). Model 2 achieved a higher recall score of 0.99 compared to 0.91 for Model 1, indicating that it correctly identified a higher proportion of actual high-risk loans out of all high-risk predictions. Although Model 1 had a slightly higher precision score, the higher recall score of Model 2 suggests that it may be more effective in identifying potential risky loans while minimizing false negatives.

Based on these results, I recommend using Model 2 for credit risk analysis tasks. Its superior performance in correctly identifying high-risk loans makes it a valuable tool for financial institutions aiming to mitigate risks associated with lending. By leveraging Model 2, the company can effectively identify and manage potential credit risks, thereby optimizing its lending decisions and maintaining a healthy loan portfolio.
