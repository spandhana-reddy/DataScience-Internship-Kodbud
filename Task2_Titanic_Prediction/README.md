# Titanic Survival Prediction

## 1. Project Overview

This project predicts whether a Titanic passenger survived using Machine Learning.

The project uses the Titanic dataset and Logistic Regression for binary classification.

## 2. Objective

The main objectives are:

- Understand the Titanic dataset.
- Clean missing and inconsistent data.
- Select relevant features.
- Convert categorical variables into numerical form.
- Split the data into training and testing sets.
- Train a Logistic Regression model.
- Evaluate the model using accuracy and classification metrics.
- Visualize the model results.

## 3. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 4. Dataset

The dataset contains information about Titanic passengers.

Important columns include:

- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

The target variable is:

- `Survived`

where:

- `0` = Did not survive
- `1` = Survived

## 5. Data Cleaning

The following steps were performed:

1. Loaded the Titanic dataset using Pandas.
2. Checked the dataset shape and structure.
3. Checked for missing values.
4. Filled missing Age values using the median.
5. Filled missing Embarked values using the mode.
6. Removed the Cabin column because it contained a large number of missing values.
7. Checked for duplicate records.

## 6. Feature Selection

The following features were selected:

- Pclass
- Sex
- Age
- SibSp
- Parch
- Fare
- Embarked

The following columns were excluded:

- PassengerId
- Name
- Ticket

## 7. Feature Encoding

The categorical variables were converted into numerical values.

`Sex` was encoded as:

- Male = 0
- Female = 1

`Embarked` was converted using one-hot encoding.

## 8. Model

Logistic Regression was used because the target variable has two possible outcomes:

- Survived
- Did not survive

The dataset was divided into:

- 80% training data
- 20% testing data

## 9. Model Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The final accuracy obtained was:

**ADD YOUR ACTUAL ACCURACY HERE**

## 10. Visualizations

The project contains visualizations showing:

- Survival distribution
- Survival by gender
- Survival by passenger class
- Age distribution
- Fare distribution
- Survival rate by gender
- Survival rate by passenger class
- Logistic Regression coefficients
- Confusion matrix

## 11. Key Findings

The analysis shows that survival was associated with passenger characteristics such as gender and passenger class.

The Logistic Regression model was able to classify passenger survival on the test dataset with the accuracy calculated during model evaluation.

## 12. Project Structure

Task2_Titanic_Prediction/

├── dataset/

│   └── train.csv

├── notebooks/

│   └── Titanic_Prediction.ipynb

├── images/

├── results/

└── README.md

## 13. Conclusion

This project provided practical experience in data cleaning, exploratory data analysis, feature engineering, feature selection, and supervised machine learning.

Logistic Regression was successfully used to predict Titanic passenger survival and evaluate the model using standard classification metrics.