# credit-card-fraud-detection-using-machinelearning
Credit Card Fraud Detection:
Overview
This project detects fraudulent credit card transactions using machine learning.
Because fraud data is highly imbalanced, accuracy is misleading, so the focus is on precision, recall, and threshold tuning.
Models Used:
Logistic Regression – High recall, used for aggressive fraud screening
Random Forest – High precision, used to reduce false positives
Both models use class_weight='balanced' and probability-based predictions.

Logistic Regression
0.76
0.90
Catch more frauds

Random Forest
0.97
0.72
Reduce customer blocking

⚖️ Key Insight
There is no single best model.
    Logistic Regression is better for high recall
    Random Forest is better for high precision
Real fraud systems combine both in a two-stage pipeline.
🛠️ Tech Stack
Python, Pandas, NumPy, Scikit-learn, Jupyter Notebook
Conclusion
Machine learning models estimate risk, not absolute truth.
Model selection depends on business cost and user experience.
