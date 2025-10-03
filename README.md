# Loan-Default-Risk-Analysis-Using-AI-Tools
Loan default risk analysis using ai tools to identify patterns in customer data.
Project Overview

This project analyzes customer demographic and financial data to predict loan default risk using AI and machine learning techniques. The primary objective is to uncover patterns that help financial institutions assess whether a customer is likely to default. Accurate identification of defaulters is crucial to reduce financial risk and improve credit decision-making.

 Tools & Technologies

Python: Data preprocessing, model training, and evaluation (pandas, scikit-learn, matplotlib, seaborn)
Excel: Initial dataset review and validation

Methodology

The workflow began with data preprocessing, where missing values were handled, categorical variables were encoded, and features were normalized. This ensured consistency in the dataset and prepared it for machine learning models.
Next, an exploratory data analysis (EDA) was conducted to identify trends and correlations. EDA revealed that factors such as co-signer presence, dependents, mortgages, employment type, and interest rate were strongly linked to default risk.
For modeling, machine learning classifiers were applied to predict defaults. The dataset was split into training and testing sets, and evaluation metrics such as accuracy, precision, recall, F1-score, and confusion matrix were used to measure performance.

Results
The model achieved an accuracy of 88.5% on the test dataset. The confusion matrix showed:
[[45051   119]
 [ 5716   184]]


The classification report highlighted:
Non-Defaulters (0) → Precision: 0.89, Recall: 1.00, F1: 0.94
Defaulters (1) → Precision: 0.61, Recall: 0.03, F1: 0.06
These results indicate that the model is highly effective at identifying non-defaulters but struggles with correctly classifying defaulters due to class imbalance in the dataset.

Insights & Outcome

The analysis confirmed that traditional models tend to be biased toward the majority class when defaults are rare. While accuracy is high, recall for defaulters remains low. This suggests the need for advanced techniques like SMOTE (Synthetic Minority Oversampling), cost-sensitive learning, or anomaly detection to improve recall for the minority class.
Overall, the project successfully delivered a data-driven loan risk prediction framework, highlighted critical risk factors, and provided recommendations for improving predictive performance in imbalanced financial datasets.




















