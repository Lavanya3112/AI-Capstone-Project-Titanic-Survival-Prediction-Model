# Titanic Survival Prediction (AI Capstone Project)

## Overview

This project presents an end-to-end machine learning pipeline to predict passenger survival on the Titanic dataset. It demonstrates the complete workflow from data preprocessing and exploratory analysis to model building, evaluation, and prediction.

---

## Objective

To build a robust classification model that predicts whether a passenger survived the Titanic disaster based on demographic and travel-related features.

---

## Dataset

The dataset includes passenger information such as:

* Age
* Gender
* Passenger Class (Pclass)
* Fare
* Embarked Location

Note: Due to file size and repository best practices, datasets are not included.
They can be downloaded from the Kaggle Titanic dataset.

---

## Workflow

### 1. Data Preprocessing

* Handled missing values using median and mode imputation
* Removed irrelevant features (Cabin, Name, Ticket)
* Encoded categorical variables (Sex, Embarked)

### 2. Feature Engineering

* Created new features such as:

  * FamilySize
  * IsAlone

### 3. Exploratory Data Analysis (EDA)

* Analyzed survival distribution
* Examined relationships between survival and key features such as gender and passenger class

### 4. Model Development

Trained and compared multiple machine learning models:

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting

### 5. Model Evaluation

* Performed train-test split for validation
* Evaluated models using:

  * Accuracy
  * Confusion Matrix
  * Classification Report

### 6. Hyperparameter Tuning

* Used GridSearchCV to optimize Random Forest parameters
* Improved model performance through cross-validation

---

## Results

* Best Model: Random Forest
* Validation Accuracy: ~82%
* Key Predictors: Gender, Passenger Class, Fare

---

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## How to Run

1. Install dependencies:

```
pip install pandas numpy scikit-learn matplotlib seaborn
```

2. Run the notebook:

```
Titanic_Survival_Prediction.ipynb
```

---

## Project Structure

* Titanic_Survival_Prediction.ipynb → Main notebook
* submission.csv → Model predictions
* README.md → Project documentation

---

## Key Insights

* Survival probability is strongly influenced by gender and passenger class
* Feature engineering improves model performance
* Ensemble models outperform simpler models

---

## Conclusion

This project demonstrates a complete machine learning workflow, highlighting the importance of preprocessing, feature engineering, model comparison, and evaluation in building effective predictive models.

---

## Future Improvements

* Incorporate advanced feature engineering (Title extraction, family grouping)
* Experiment with boosting algorithms such as XGBoost or LightGBM
* Improve model interpretability

---

## Author

Lavanya Dive
BSc Data Science Student
