# Space Titanic Prediction (Decision Tree)

This project uses the **Space Titanic dataset from Kaggle** to predict whether a passenger was transported to another dimension during the spaceship incident.

## Project Objective
Build a machine learning model that predicts the `Transported` status of passengers using demographic and spending features.

## Dataset
Dataset source: Kaggle – Space Titanic Competition

Files included in this repository:

data/
- train.csv
- test.csv

Other files:
- space_titanic_model.ipynb → complete analysis and model training
- submission.csv → prediction file used for Kaggle submission

## Workflow
1. Data Loading
2. Data Cleaning and Handling Missing Values
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Train / Validation Split
6. Model Training using Decision Tree
7. Prediction on Test Data
8. Kaggle Submission File Creation

## Model Used
Decision Tree Classifier

Parameters:
max_depth = 6  
random_state = 42

## Validation Accuracy
Approximately **0.76**

## Tools & Libraries
Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  
Scikit-learn

## Project Structure
space-titanic-decision-tree
│
├── data
│   ├── train.csv
│   └── test.csv
│
├── space_titanic_model.ipynb
├── submission.csv
└── README.md
