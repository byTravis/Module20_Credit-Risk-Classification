# Module 20 - Credit Risk Classification
*Credit Risk Classification - Supervised Machine Learning Challenge - Week 20 - Data Analytics Boot Camp - University of Oregon*

![Credit Risk Classification](images/project_banner.jpg)

## Background
I'm using a Logistic Regression Model to train and evaluate a model based on loan risk. I used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of new borrowers.  The training data includes loan size, interest rate, borrower income, debt to income, number of accounts, number of derogatory marks, and total debt.  These are compared to the loan status of fulfilled loans or defaulted loans.  I split the data into training and testing sets to create the model.  The result is a model that will help us predict whether a new loan is likely to be healthy or high risk.


## Results
### Classification Report:

![Classification Report](images/classification_report.JPG)

**Healthy Loan (0):**
- Precision: 1.00 
    - Among all the loans predicted as healthy, 100% are actually healthy.
- Recall: 1.00 
    - Among all the actual healthy loans, 100% are correctly predicted as healthy.

**High Risk Loan (1):**
- Precision: 0.87
    - Among all the loans predicted as high risk, 87% are actually high risk.
- Recall: 0.89
    - Among all the actual high-risk loans, 89% are correctly predicted as high risk.

### Confusion Matrix
![Confusion Matrix](images/confusion_matrix.png)


## Summary

This model works very well in predicting healthy loans with perfect precision and recall of 1.  High risk loans also seem to perform well with .87 precision and .89 recall.  Overall, the model achieves a high accuracy of 99%, which suggests it does exceptionally well in distinguishing between healthy and high-risk loans.