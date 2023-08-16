# credit-risk-classification

Credit Risk Analysis Report


The purpose of the exercise is to create a classifier model that allow us to make predictions about the loan status of the clients (0 = healthy, 1 = high risk), based on different values as loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt.

I’m glad to announce that the model works perfectly, after making some adjustments especially on the balance of the number of data points, with a precision of 0.99% the model shows us the next classification:

		precision    recall  f1-score   support
   0       	   0.99      0.99      0.99     56277
   1       	   0.99      0.99      0.99     56277

accuracy                        	 0.99    112554



•	Precision: With this metric can estimate how successful will be the classifier to detect the future status for the loans. As we can see both type of status has a precision of 99%.
•	Recall: Is the ability of our model to identify the relevant data point. We have a recall of 99%.
•	F1-score: This value is just the combination of the precision and recall values, also we have a score of 99%.
•	Support: Is the number of samples that we have for both loans.
•	Accuracy: Estimate the percentage of cases that model has succeeded in classify, this value needs to be interpreted with attention, because to have a representative accuracy the number of samples needs to be similar. 

I highly recommend to use the model, it can help the company to identify future the creditworthiness of borrowers and avoid risk loans.
