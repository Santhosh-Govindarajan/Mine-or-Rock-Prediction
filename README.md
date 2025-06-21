# Sonar Signal Classification – Mine vs Rock using Logistic Regression

## 📌 Overview

This project uses a dataset of continuous sonar wave readings to predict whether the detected object is a **mine** or a **rock**. Given the binary nature of the target variable, we implement a **Logistic Regression** model — a classic and effective choice for classification problems.

## 🎯 Objective

To build a machine learning model that can classify an object based on sonar signals as either:
- **Mine**
- **Rock**

## 📊 Dataset Details

- All features are **continuous sonar frequency values**
- Target column: Binary classification (Mine = 1, Rock = 0)
- Dataset Source: [UCI Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+sonar+mines+vs.+rocks)

## 🧹 Steps Involved

1. **Data Cleaning**: Verified for missing/null values, outliers, and ensured uniform formatting.
2. **Feature Analysis**: Explored sonar signal distributions, patterns, and relationships.
3. **Model Selection**: Used **Logistic Regression** for its interpretability and performance on binary classification.
4. **Data Splitting**: Divided the data into **training (80%)** and **testing (20%)** sets.
5. **Model Evaluation**: Achieved an **accuracy of 71.4%**, indicating decent performance for a baseline model using basic preprocessing and no hyperparameter tuning.

## 💡 Why Logistic Regression?

- Perfectly suited for binary classification problems
- Provides probability-based predictions
- Easy to interpret coefficients and understand feature impact
- Lightweight and performs well on smaller datasets

## 📈 Future Improvements

- Try advanced models like **Random Forest**, **SVM**, or **XGBoost** for improved accuracy
- Perform **feature engineering** or **dimensionality reduction**
- Use **cross-validation** and **grid search** for better generalization

## 🔧 Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
