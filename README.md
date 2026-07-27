# Customer Churn Prediction

**Participant Name:** Archit Ravikumar  
**MUID:** architravikumar@mulearn

---

## Business Objective

The objective of this project is to predict whether a customer is likely to churn based on their demographic details and service usage. Predicting churn helps businesses identify customers who are at risk of leaving so that they can take suitable retention measures.

---

## Dataset Overview

The Customer Churn dataset contains customer-related information such as age, subscription details, usage frequency, support interactions, payment delay, and spending history. These features are used to train machine learning models for churn prediction.

---

## Features & Target Variable

### Features

- CustomerID
- Age
- Gender
- Tenure
- Usage Frequency
- Support Calls
- Payment Delay
- Subscription Type
- Contract Length
- Total Spend
- Last Interaction

### Target Variable

- **Churn**
  - 1 → Customer Churned
  - 0 → Customer Retained

---

## Preprocessing Pipeline

The following preprocessing steps were performed:

- Checked dataset information
- Verified missing values
- Checked duplicate records
- Removed rows with missing target values (if any)
- Separated features and target variable
- Applied StandardScaler for feature scaling
- Split the data into training and testing sets

---

## Models Implemented

Three classification models were trained and compared:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

---

## Performance Comparison

| Model | Accuracy | Precision | Recall | F1-Score |
|--------|---------:|----------:|--------:|---------:|
| Logistic Regression | **0.5866** | **0.5346** | **0.9825** | **0.6925** |
| Decision Tree | 0.5034 | 0.4882 | 0.9987 | 0.6558 |
| Random Forest | 0.5034 | 0.4882 | 0.9987 | 0.6558 |

---

## Best Model

Based on the evaluation metrics, **Logistic Regression** performed better than the other models. It achieved the highest Accuracy and F1-Score, making it the most suitable model for this customer churn prediction task.

---

## Key Observations

- Logistic Regression achieved the best overall performance.
- Decision Tree and Random Forest produced similar results on this dataset.
- Recall values are high, indicating that most churn cases were identified.
- There is still room for improving the overall prediction accuracy.

---

## Business Recommendations

- Identify customers with a high probability of churn and offer personalized retention plans.
- Improve customer support response time to increase customer satisfaction.
- Regularly monitor customer activity to detect early signs of churn.

---

## Future Improvements

- Perform feature selection to identify the most important features.
- Tune model hyperparameters for better performance.
- Experiment with additional algorithms such as XGBoost or LightGBM.
- Use cross-validation for more robust model evaluation.
