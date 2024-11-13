# credit-risk-classification
Results
The machine learning model's performance can be summarized with the following metrics:
Accuracy Score: 99.25%
This indicates that the model correctly predicted the loan status (healthy or high-risk) for 99.25% of all loans in the test set.
Precision Scores:
Healthy Loans (0): 99.81%
High-Risk Loans (1): 84.13%
The model is highly precise in identifying healthy loans, with only a small percentage of false positives. For high-risk loans, the precision is lower but still good, indicating some healthy loans may be misclassified as high-risk.
Recall Scores:
Healthy Loans (0): 99.41%
High-Risk Loans (1): 94.19%
The model has excellent recall for both categories, especially for high-risk loans, meaning it catches a high percentage of actual high-risk loans.
Summary
The logistic regression model demonstrates strong performance in predicting both healthy and high-risk loans:
The overall accuracy of 99.25% suggests that the model is highly reliable in classifying loans correctly.
The model excels at identifying healthy loans, with both precision and recall above 99%. This means it rarely misclassifies healthy loans as high-risk.
For high-risk loans, the model shows a good balance between precision (84.13%) and recall (94.19%). The high recall is particularly important as it indicates the model is effective at catching most of the actual high-risk loans.
The slightly lower precision for high-risk loans suggests that the model tends to be conservative, sometimes flagging healthy loans as high-risk. In the context of credit risk, this conservative approach can be seen as a positive feature, as it's generally better to be cautious with potential high-risk loans.
