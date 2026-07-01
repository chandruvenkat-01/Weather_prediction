# Weather_prediction
# Rain Prediction using Machine Learning

## Project Overview

This project predicts whether it will rain based on historical Australian weather data. The workflow includes data preprocessing, feature engineering, handling class imbalance, model training, and performance evaluation using multiple machine learning algorithms.

---

## Dataset

- Australian Weather Dataset
- Target Variable: RainToday

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- XGBoost

---

## Project Workflow

### 1. Data Loading

- Imported weather dataset
- Inspected data types and missing values

### 2. Data Cleaning

- Filled missing numerical values using Mean and Median
- Filled categorical missing values using Mode
- Converted categorical features into numerical format

### 3. Feature Engineering

- One-Hot Encoding for categorical variables
- Selected input features and target variable

### 4. Handling Imbalanced Data

- Applied SMOTE for oversampling
- Used Random Under Sampling to balance the classes

### 5. Model Building

Implemented and compared:

- K-Nearest Neighbors
- Logistic Regression
- Decision Tree
- XGBoost Classifier

### 6. Model Evaluation

Evaluated models using:

- Accuracy
- Precision
- Recall
- F1 Score
- Classification Report

---

## Project Structure

```
Weather.ipynb
weatherAUS.csv
README.md
```

---

## Libraries Used

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
xgboost
```

---

## Learning Outcomes

- Data preprocessing
- Missing value handling
- Feature encoding
- Handling imbalanced datasets
- Building ML pipelines
- Comparing classification models
- Model evaluation using classification metrics

---

## Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- Feature selection
- Deployment using Streamlit or Flask
- Model explainability using SHAP
