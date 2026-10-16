# Machine Learning Tasks Collection

This repository contains three machine learning projects implemented in
Python using Jupyter Notebooks. The tasks cover **credit default
prediction**, **handwritten character recognition**, and **heart disease
prediction**.

## Projects

### 1. Credit Scoring Model

**Folder:** `Credit_Scoring_Model`

This project predicts whether a credit card customer is likely to
default on their next payment.

#### Dataset

-   File: `default of credit card clients.xls`
-   Records: 30,000
-   Features after feature engineering: 26
-   Target: `default payment next month`

#### Methodology

-   Loaded the Excel dataset using Pandas
-   Checked dataset information, missing values, and duplicates
-   Removed duplicate records
-   Created:
    -   `TOTAL_BILL_AMT`
    -   `TOTAL_PAY_AMT`
-   Split the data into training and testing sets using an 80/20 split
-   Applied `StandardScaler`
-   Trained a **Logistic Regression** model
-   Evaluated the model using accuracy, precision, recall, F1-score,
    ROC-AUC, confusion matrix, and ROC curve
-   Tested the model with a sample customer

#### Results

  Metric                  Result
  --------------------- --------
  Accuracy                80.82%
  Precision (Default)     68.97%
  Recall (Default)        24.11%
  F1-Score (Default)      35.73%
  ROC-AUC                 70.78%

## Important Notes

-   The notebooks contain the complete data preprocessing, model
    training, evaluation, and prediction workflow.
-   Results can vary slightly when the notebooks are retrained in a
    different environment or with different library versions.
-   The credit scoring model is also intended for educational purposes
    and should not be treated as a production financial decision system
    without further validation.

## Author

**Muhammad Khursheed**

**BSCS --- Minhaj University Lahore**

## License

This project is intended for educational and academic purposes.
