📉 Customer Churn Prediction
Overview
This project uses multiple machine learning models to predict whether a bank customer will leave (churn) or stay with the bank based on their demographic and financial profile.

Dataset
The dataset tracks customer account characteristics, including:

Credit score

Customer age and gender

Account balance and number of bank products used

Estimated salary

Target classes (Exited):

0 = Stayed (Retained customer)

1 = Left (Churned customer)

Steps Performed
Missing value validation and removing unnecessary profile features (e.g., Surnames).

Categorical encoding using LabelEncoder for string categories.

Exploratory visualization comparing customer age, balance, and gender distributions against churn rates.

Train-test data splitting with stratification to handle class imbalance.

Feature scaling using StandardScaler.

Evaluation and cross-model performance comparison.

Models Used
Logistic Regression

Support Vector Machine (SVM)

Decision Tree

Random Forest

XGBoost

Evaluation Metrics
Accuracy

Precision

Recall

F1-score

ROC-AUC Curve

Confusion Matrix

Technologies
Python

Pandas & NumPy

Matplotlib & Seaborn

Scikit-learn

XGBoost

Jupyter Notebook

Conclusion
This project applies a full classification pipeline to compare linear, tree-based, and ensemble boosting models, identifying the best architecture for predicting customer attrition.
