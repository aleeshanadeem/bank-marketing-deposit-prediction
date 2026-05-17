# Bank Marketing Dataset – Deposit Prediction (81% Accuracy)

## Project Overview
This project focuses on predicting whether a customer will subscribe to a bank term deposit using machine learning techniques. The analysis is performed on a Bank Marketing dataset and includes data preprocessing, visualization, feature preparation, and model building.

The goal is to understand customer behavior and build a predictive model that can help identify potential deposit subscribers.

---

## Dataset Information

The dataset contains customer information collected from bank marketing campaigns.

### Features include:
- Age
- Job
- Marital Status
- Education
- Balance
- Housing Loan
- Personal Loan
- Contact Type
- Campaign Information
- Previous Outcomes
- Deposit Status (Target Variable)

**Target Variable:** `deposit`

- `yes` → Customer subscribed
- `no` → Customer did not subscribe

---

## Project Workflow

### 1. Data Loading
- Imported dataset using Pandas
- Initial exploration of records and columns

### 2. Data Visualization
Performed exploratory analysis using visualizations to understand:
- Category distributions
- Feature patterns
- Customer behavior insights

### 3. Data Preprocessing
- Encoded categorical variables using Label Encoding
- Prepared features and target variable
- Handled machine learning input format

### 4. Train-Test Split
Dataset split:
- Training: 80%
- Testing: 20%

Stratified splitting used to maintain class balance.

### 5. Machine Learning Model
Model used:

**Decision Tree Classifier**

Configuration:
- `max_depth = 5`
- `random_state = 42`

---

## Model Performance

### Accuracy Achieved:
**81%**

The Decision Tree Classifier showed balanced and reliable performance for deposit prediction.

---

## Libraries 

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Key Insight

The analysis and visualizations helped identify important customer patterns that may influence deposit subscription decisions.

---

## Conclusion

The Decision Tree Classifier achieved **81% accuracy**, demonstrating effective prediction performance while maintaining model interpretability.

Further improvements can be achieved using:
- Hyperparameter tuning
- Random Forest
- XGBoost
- Feature engineering

---

## Author

**Aleesha Nadeem**

2(AN)K

Learning Journey: Machine Learning | Data Science | Kaggle
