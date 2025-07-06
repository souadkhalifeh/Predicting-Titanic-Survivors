# Project: Predicting Titanic Survivors

# 🧠 Project Goal:
Build a machine learning model that predicts whether a passenger survived the Titanic disaster based on features such as age, sex, ticket class, and more.

# 📦 Dataset:
Titanic Dataset on Kaggle: ([https://www.kaggle.com/datasets/yasserh/titanic-dataset](https://www.kaggle.com/competitions/titanic/data))

Contains two files:
- train.csv: With labels (Survived: 0 = No, 1 = Yes)
- test.csv: Without labels (used for final prediction submission)

# 📊 Input Features Include:
- Pclass: Ticket class (1st, 2nd, 3rd)
- Sex: Gender
- Age: Age in years
- SibSp: # of siblings/spouses aboard
- Parch: # of parents/children aboard
- Fare: Passenger fare
- Embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
- Cabin, Ticket, Name (can be engineered)

# ✅ Target Variable:
- Survived: 0 or 1

# 🛠️ Project Steps:
1. Exploratory Data Analysis (EDA):
    - Understand data distributions and class imbalance
    - Visualize survival rate across different features (e.g., male vs. female, age groups, ticket class)
2. Data Preprocessing:
    - Handle missing values (e.g., fill age using median or predictive imputation)
    - Encode categorical features (e.g., one-hot or label encoding for Sex, Embarked)
    - Feature engineering (e.g., extract title from Name, bin Age into groups)
3. Model Building:
     - Try models like Logistic Regression, Random Forest, or XGBoost
     - Use cross-validation for model robustness

4. Evaluation:
     - Use accuracy, precision, recall, and confusion matrix

5. Bonus (Advanced):
       -Hyperparameter tuning using GridSearchCV



📌 Learning Outcomes:
- Apply supervised classification techniques
- Practice data wrangling and feature engineering
- Evaluate model performance using appropriate metrics
- Understand how data bias (e.g., gender, class) can affect predictions

## Disclaimer: 
This is part of The AIEngineers Program by Lara Wehbe
