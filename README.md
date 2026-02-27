# Customer Churn Prediction – Telco Industry

This project aims to predict customer churn for a telecommunications company using Machine Learning. Being able to identify customers who are likely to cancel their subscription allows businesses to take proactive measures (such as loyalty programs or discounts) to retain them. **Model will be improved!**

# 📊 Model Performance
I implemented a Random Forest Classifier, which achieved a solid baseline. Here are the key metrics from the final evaluation:

Overall Accuracy: 80%

Precision (Class 1 - Churn): 68% (When the model predicts churn, it is correct 68% of the time).

Recall (Class 1 - Churn): 47% (The model successfully identifies 47% of all actual churners).

# 🛠️ Tech Stack
Language: Python

Libraries: Pandas, Scikit-learn, Matplotlib

Environment: Google Colab

# 🧠 Key Learnings & Challenges
Data Cleaning: Handled mixed types in the TotalCharges column and managed missing values.

Feature Engineering: Applied One-Hot Encoding using pd.get_dummies(drop_first=True) to convert categorical data into numerical format suitable for ML.

Class Imbalance: Discovered that the dataset has significantly more "Stayed" than "Churned" customers, which explains why the model is better at predicting the majority class.
