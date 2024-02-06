# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis. The purpose of this analysis was to predict which loans are high risk vs healthy
* Explain what financial information the data was on, and what you needed to predict.the financial data came from the credit risk csv and we used loan_size	interest_rate	borrower_income	debt_to_income	num_of_accounts	derogatory_marks	total_debt	loan_status to calculate the status
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

* Describe the stages of the machine learning process you went through as part of this analysis. preped data, then trained the model to create a logistical regression which was used to evaluate the performance of the loan 

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).preped data, then trained the model to create a logistical regression which was used to evaluate the performance of the loan 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

Balanced Accuracy Score:
Original Data: Approximately 0.95
Precision:
Healthy Loan (0): 1.00
High-risk Loan (1): 0.85
Recall:
Healthy Loan (0): 0.99
High-risk Loan (1): 0.91


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

Balanced Accuracy Score:
Resampled Data: Approximately 0.99
Precision:
Healthy Loan (0): 1.00
High-risk Loan (1): 0.85
Recall:
Healthy Loan (0): 0.99
High-risk Loan (1): 0.99

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? ) I recommend using model two because it is more accurate. I think that both would be good to use because they both have high accuracy.

If you do not recommend any of the models, please justify your reasoning.
