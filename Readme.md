# Logistic Regression on Breast Cancer Wisconsin Dataset

Objective

Build a binary classifier using Logistic Regression to predict whether a tumor is malignant (M) or benign (B).


Steps Followed

1. Data Preprocessing

Loaded the dataset and dropped irrelevant columns (id, Unnamed: 32)

Encoded the diagnosis column (M → 1, B → 0)

Split the data into training and test sets

Scaled features using StandardScaler


2. Model Training

Used LogisticRegression from scikit-learn

Trained the model on the preprocessed data


3. Evaluation

Accuracy: 96.49%

Confusion Matrix:

[[76  4]
 [ 0 34]]

Classification Report:

Precision for benign (0): 1.00

Precision for malignant (1): 0.89

F1-score overall: High, indicating strong performance
