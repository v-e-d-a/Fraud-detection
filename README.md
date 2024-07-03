# Fraud-detection

# Training 
Feature Selection: For simplicity, only the amt column is used as a numeric feature.

Preprocessing: Only amt is passed to StandardScaler for scaling since it's the only numeric column in this example.

Model Training and Evaluation: RandomForestClassifier is trained on the scaled amt column and evaluated for its performance in predicting fraud.

# Diagrams 

Confusion Matrix: Visualizes true positives, true negatives, false positives, and false negatives in a matrix format. Adjust labels (Not Fraud, Fraud) based on your binary classification.

ROC Curve: Displays the trade-off between sensitivity (true positive rate) and specificity (true negative rate). AUC (Area Under the Curve) quantifies overall performance.
