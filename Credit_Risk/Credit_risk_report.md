## Overview of the Analysis

Purpose of the Analysis: The objective of this analysis is to evaluate the performance of a logistic regression model in predicting credit risk. Specifically, we aim to determine how well the model can classify loans into two categories: healthy loans (0) and high-risk loans (1). This assessment helps in making informed lending decisions and managing credit risk effectively.

Financial Information: The dataset includes various financial attributes of borrowers, such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The target variable, loan_status, indicates whether a loan is healthy (0) or high-risk (1).

* Variables:

    loan_size: The size of the loan in dollars.

    interest_rate: The interest rate associated with the loan.

    borrower_income: The annual income of the borrower.

    debt_to_income: The debt-to-income ratio of the borrower.

    num_of_accounts: The number of accounts held by the borrower.

    derogatory_marks: The number of derogatory marks on the borrower's credit report.

    total_debt: The total debt amount of the borrower.

    loan_status: The status of the loan (0 for healthy, 1 for high-risk).

* Machine Learning Process:

    Data Preprocessing: Cleaned the dataset, handled missing values, and performed feature scaling.

    Feature Selection: Identified relevant features for the model.

    Model Training: Trained the logistic regression model using the preprocessed data.

    Model Evaluation: Assessed the model's performance using metrics such as accuracy, precision, recall, and F1-score.
## Results

* Model Performance:

    Overall Accuracy: 99%

    * Healthy Loans (0):

        Precision: 1.00

        Recall: 0.99

        F1-score: 1.00

    * High-Risk Loans (1):

        Precision: 0.84

        Recall: 0.94

        F1-score: 0.89

    The logistic regression model demonstrates outstanding performance in predicting credit risk, with an overall accuracy of 99%. Here’s a breakdown of the key findings:
* Healthy Loans (0):
    * The model exhibits perfect precision (1.00) and near-perfect recall (0.99), indicating that it is highly effective at correctly identifying healthy loans and making very few false-positive predictions.
* High-Risk Loans (1):
    * The model has a precision of 0.84 and a recall of 0.94. This means that while it correctly identifies 94% of actual high-risk loans, there is a 16% chance of false positives (predicting a loan as high-risk when it is not).

## Summary


* Performance: 
    The logistic regression model exhibits exceptional performance in predicting healthy loans with near-perfect precision and recall. For high-risk loans, the model demonstrates good performance with high recall, ensuring that most high-risk loans are correctly identified. However, there is a slight drop in precision, indicating some false positives.

* Recommendation: 
    Based on the results, I recommend using the logistic regression model for credit risk assessment. Its high accuracy and strong performance in identifying both healthy and high-risk loans make it a reliable tool for the company. Although there are some false positives for high-risk loans, the model's high recall ensures that most high-risk cases are detected, which is crucial for managing credit risk. Additional checks can be implemented to handle false positives effectively.

* Overall 
    The logistic regression model provides a robust balance between precision and recall, particularly in identifying high-risk loans, making it suitable for informed lending decisions.
