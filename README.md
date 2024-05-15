# credit-risk-classification
Module 20 challenge

The purpose of this analysis is to determine the accuracy of the regression model in identifying healthy loans versus high-risk loans. 

Results:
Precision-
	Healthy Loans: 100%
	High-Risk Loans: 86%
Recall-
	Healthy Loans: 100%
	High-Risk Loans: 91%
F1-Score-
	Healthy Loans: 1.00 (very accurate)
	High-Risk Loans: .88(accurate)
Support-
	Healthy Loans: 15,001 instances
	High-Risk Loans: 507 instances
Accuracy-
The regression model is correct 99% of the time in predicting whether a loan is ‘healthy’ or ‘high-risk’.
Macro Average-
	Precision: 0.93  |  Recall: 0.95  |  F1-score:  0.94
Weighted Average-
	Precision: 0.99  |  Recall: 0.99  |  F1-score:  0.99
	
	

This logistic regression model preforms well in predicting healthy loans with a high degree of precision(100%), recall(100%) and overall accuracy(1.00). It also did will in predicting high risk loans, but had slightly less accurate predictions in terms of precision(86%). This could possibly be due to the difference in the sample sizes, with the high-risk loan sample(507) size being smaller than the healthy loan sample size(15,001). At this time, I would recommend using this regression model in identifying healthy or high-risk type loans. However, I do think it would be prudent to repeat this regression models periodically to determine it’s continued accuracy as our sample sizes grow. 
