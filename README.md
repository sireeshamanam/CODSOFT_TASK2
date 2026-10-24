# CODSOFT_TASK2
Credit Card Fraud Detection using Machine Learning

# Credit Card Fraud Detection

## Project Overview
This project uses Machine Learning to identify potentially fraudulent credit card transactions.

## Dataset
The dataset contains 284,807 transactions and 31 columns, including the target column `Class`.

- `0` – Normal transaction
- `1` – Fraudulent transaction

Dataset: [Credit Card Fraud Detection – Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib

## Models Used
1. Logistic Regression
2. Random Forest Classifier

## Workflow
1. Load and explore the dataset.
2. Visualize normal and fraudulent transactions.
3. Split the dataset into training and testing sets.
4. Train Logistic Regression and Random Forest models.
5. Evaluate the models using accuracy, precision, recall, F1-score, and confusion matrices.
6. Save the trained Random Forest model.

## Results

| Metric | Logistic Regression | Random Forest |
|---|---:|---:|
| Accuracy | 97.55% | 99.95% |
| Precision | 6.10% | 96.05% |
| Recall | 91.84% | 74.49% |
| F1-score | 11.44% | 83.91% |

Random Forest achieved the highest accuracy, precision, and F1-score in this experiment. However, it missed some fraudulent transactions, so recall remains an important area for improvement.

## Conclusion
This project demonstrates how Machine Learning can help detect fraudulent credit card transactions. The models were compared using multiple evaluation metrics because the dataset is highly imbalanced. Random Forest provided the better overall balance in this experiment.

## Internship
CodSoft Machine Learning Internship – Task 2
