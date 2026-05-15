# Titanic Survival Prediction

## Project Overview
This machine learning project predicts whether a passenger survived the Titanic disaster based on passenger information such as age, gender, ticket class, fare, and family details.

## Problem Statement
Build a classification model to predict passenger survival using historical Titanic dataset records.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Models Implemented
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

## Project Workflow
1. Data loading and exploration
2. Data cleaning and preprocessing
3. Handling missing values
4. Feature encoding
5. Train-test split
6. Feature scaling (for KNN)
7. Model training
8. Model evaluation and comparison

## Data Preprocessing
- Removed non-useful columns:
  - PassengerId
  - Name
  - Cabin
  - Ticket
- Filled missing values:
  - Age → Median value
  - Embarked → Mode value
- Encoded categorical variables:
  - Sex
  - Embarked

## Model Performance
### K-Nearest Neighbors (KNN)
- Accuracy: ~80.4%

### Gaussian Naive Bayes
- Accuracy: ~77.1%

## Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1 Score

## Repository Contents
- `KNN_and_Naive_Bayes.ipynb` → Jupyter Notebook
- `titanic.csv` → Dataset
- `README.md` → Project documentation

## Learning Outcome
This project helped strengthen understanding of:
- Data preprocessing
- Feature engineering basics
- Classification algorithms
- Model evaluation
- Machine learning workflow
