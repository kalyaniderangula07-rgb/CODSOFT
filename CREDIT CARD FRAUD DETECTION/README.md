# Credit Card Fraud Detection

## Project Overview

The Credit Card Fraud Detection project aims to identify fraudulent credit card transactions using machine learning techniques. The model analyzes transaction data and classifies transactions as either genuine or fraudulent.

## Objective

To build a machine learning model that can accurately detect fraudulent credit card transactions and help reduce financial losses caused by fraud.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Methodology

### 1. Data Collection
Loaded and explored the credit card transaction dataset.

### 2. Data Preprocessing
- Checked for missing values.
- Normalized transaction features.
- Prepared the dataset for model training.

### 3. Handling Class Imbalance
Since fraudulent transactions were much fewer than genuine transactions, undersampling was used to balance the dataset.

### 4. Model Training
Trained Logistic Regression and Random Forest models on the balanced dataset.

### 5. Model Evaluation
Evaluated model performance using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Results

Both models successfully detected fraudulent transactions with high performance. The models achieved strong Precision, Recall, and F1-Scores, demonstrating their effectiveness in fraud detection.

## Conclusion

A machine learning-based fraud detection system was successfully developed to classify credit card transactions as genuine or fraudulent. The project demonstrated the importance of data preprocessing, handling imbalanced datasets, and evaluating classification models for real-world fraud detection applications.

