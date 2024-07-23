# Binary-Classification-of-Insurance-Cross-Selling
## Kaggle Competition 
To see the test and train data, visit:
https://www.kaggle.com/competitions/playground-series-s4e7/data
 
 
## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Results](#results)
 

## Introduction
 The goal of this competition is to predict which customers respond positively to an automobile insurance offer.

## Dataset
The dataset used for this project contains information about customers, including demographic details, driving history, and insurance policy information. The key columns in the dataset are:

- `id`: Unique identifier for each customer
- `Gender`: Gender of the customer (0: Female, 1: Male)
- `Age`: Age of the customer
- `Driving_License`: Whether the customer has a driving license (0: No, 1: Yes)
- `Region_Code`: Code representing the region of the customer
- `Previously_Insured`: Whether the customer already has insurance (0: No, 1: Yes)
- `Vehicle_Age`: Age of the vehicle (1: < 1 Year, 2: 1-2 Year, 3: > 2 Years)
- `Vehicle_Damage`: Whether the customer has had any vehicle damage (0: No, 1: Yes)
- `Annual_Premium`: The annual premium amount
- `Policy_Sales_Channel`: Code representing the sales channel through which the policy was sold
- `Vintage`: Number of days the customer has been associated with the company
- `Response`: Target variable (0: Not Interested, 1: Interested)


## Feature Engineering
Feature engineering techniques applied in this project include:

- Encoding categorical variables
- Creating new features based on domain knowledge
- Scaling numerical features

## Modeling
Various machine learning models have been experimented with, including:

- Logistic Regression
- Random Forest
- Gradient Boosting
- XGBoost
- LightGBM
- CatBoost

Hyperparameter tuning has been performed using techniques such as Grid Search and Random Search to optimize model performance.

## Evaluation
The models are evaluated using metrics such as:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

## Results
Progress: Initial model achieved 0.88569 score and the best score is 0.89692. 
 
 
 
