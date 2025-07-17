# Customer Churn Prediction
This project focuses on predicting customer churn using machine learning techniques. Churn refers to customers who stop using a company’s service. Accurately predicting churn can help businesses take proactive measures to retain customers and reduce losses.

------------------
# ✅ Project Overview

- Goal: Predict whether a customer will churn based on their usage behavior and service details.
- Target Variable: Churn (1 = Churned, 0 = Stayed)

--------------------
# 🔄 Data Preprocessing

- Oversampling was applied using RandomOverSampler to balance the dataset and reduce bias toward the majority class.

-------------------
# 🤖 Models Used

1. Logistic Regression
- A baseline model used for binary classification.

- Simple and interpretable.

- Accuracy was acceptable, but had room for improvement.

2. Random Forest Classifier
- Ensemble learning method for better performance.

- Improved accuracy and generalization on the test set.

- Outperformed logistic regression in both train and test metrics.

---------------

# 📈 Evaluation: Confusion Matrix

Both models were evaluated using confusion matrices on train and test sets:

- Visualized with Seaborn heatmaps

- Metrics observed:

      - True Positives (Churn correctly predicted)

      - True Negatives (Stayed correctly predicted)

      - False Positives / False Negatives (Incorrect predictions)

  -----------------------
 # 📌 Conclusion
 
- The Random Forest model provided better accuracy and prediction capability compared to Logistic Regression.

- Oversampling helped improve performance by handling data imbalance.

- The project demonstrates the importance of feature selection, preprocessing, and model evaluation for classification tasks.


