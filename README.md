# 📊 Customer Churn Prediction with Logistic Regression

This project applies **Logistic Regression** to predict customer churn based on user data like age, tenure, income, and service usage. The goal is to identify which customers are likely to leave, helping businesses take action before it’s too late.

## 📁 Dataset

The dataset `ChurnData.csv` contains:
- Demographics (age, income, education)
- Service features (tenure, callcard, wireless usage)
- Label: `churn` (1 if customer left, 0 otherwise)

## 🔧 Process

1. Data preprocessing and selection of key features
2. Normalization using `StandardScaler`
3. Train-test split (80/20)
4. Model training with `LogisticRegression`
5. Evaluation with:
   - Accuracy
   - Jaccard score
   - Confusion matrix
   - Classification report
   - Log loss

## 📊 Results

- **Accuracy:** 75%
- **Jaccard Score (class 0):** 0.697
- **Log Loss:** 0.571
- **F1-scores:** 0.82 (class 0), 0.58 (class 1)


## 🧠 Tools Used

- Python
- NumPy, Pandas
- scikit-learn
- Matplotlib

## 💬 Notes

This project is part of a machine learning learning path and demonstrates the basic application of logistic regression for binary classification problems.
