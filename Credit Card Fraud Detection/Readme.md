## Summary

The Credit Card Fraud Detection project aims to develop a reliable and accurate model for identifying fraudulent transactions from a dataset of credit card transactions. By leveraging multiple machine learning algorithms, the project seeks to determine the most effective model for this binary classification task. The ultimate goal is to provide a tool that can accurately flag potentially fraudulent transactions, helping to protect consumers and financial institutions from fraud.

To achieve optimal performance in fraud detection, three different machine learning models were employed: Logistic Regression, Random Forest Classifier, and Support Vector Machine (SVM). Each model was evaluated based on its performance metrics, including precision, recall, and the F1-score—key indicators of how well the model identifies fraudulent transactions while minimizing false positives.

1. Logistic Regression Model

* Accuracy: 99%

* AUC Score: 92%

* Performance: The Logistic Regression model achieved high scores in accuracy and AUC, indicating its effectiveness in distinguishing between fraudulent and legitimate transactions. It performed exceptionally well, providing a reliable benchmark for comparison with other models.

2. Random Forest Classifier Model

* Accuracy: 99%

* AUC Score: 95%

* Performance: The Random Forest Classifier also performed admirably, matching the accuracy of the Logistic Regression model but surpassing the AUC score of the model. By utilizing an ensemble of decision trees, this model enhanced predictive performance and robustness, proving to be a strong competitor in fraud detection.

Given the Random Forest model's exceptional performance, it was selected as the foundation for developing the fraud detection tool. This tool allows users to input transaction details and receive an assessment of whether the transaction is potentially fraudulent based on the trained model. The user-friendly interface ensures that even those without technical expertise can easily use the tool to enhance security and prevent fraud.

The Credit Card Fraud Detection project successfully identified the Random Forest model as the most accurate and reliable method for fraud detection. With its high accuracy and AUC, this model demonstrated its capability to accurately identify fraudulent transactions, providing valuable protection for users and financial institutions
