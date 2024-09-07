# Housing Price Prediction - EDA & Feature Engineering
## Overview
This project focuses on analyzing and transforming a dataset to predict housing prices. It involves two main parts: Exploratory Data Analysis (EDA) to understand the data, and Feature Engineering to prepare the data for machine learning models. The dataset used is sourced from Kaggle, with the goal of predicting house prices based on various features.

## Contents
### 1. Exploratory Data Analysis (EDA)
#### Data Loading: Load the dataset and explore its structure.
#### Initial Data Exploration: Perform basic statistical analysis to understand the overall data.
#### Missing Values: Identify missing values in both categorical and numerical features and visualize them.
#### Numerical Features: Analyze numerical features to assess their distribution and relationship with house prices.
#### Year-Related Features: Investigate how features like construction year or remodel year affect house prices.
### 2. Feature Engineering
#### Handling Missing Data: Apply appropriate strategies to handle missing values in categorical and numerical features to ensure completeness of the dataset.
#### Log Transformation: Apply logarithmic transformation to numerical features that are highly skewed to make them more normally distributed and improve model performance.
#### Rare Label Encoding: Identify rare categories in categorical variables and group them into a single category to avoid overfitting.
#### Categorical Feature Encoding: Convert categorical features into numerical values by encoding them based on their impact on the target variable.
#### Feature Scaling: Scale numerical features to a consistent range using techniques like Min-Max Scaling, which ensures that the model interprets all features on the same scale.
## Summary
Exploratory Data Analysis (EDA) is performed to get a clear understanding of the data and its structure.
Feature Engineering steps like missing value imputation, log transformation, encoding, and scaling are applied to ensure that the data is clean and well-prepared for model building.
Acknowledgments
The dataset is from Kaggle. Special thanks to Krish Naik for his tutorials and guidance in developing this project.

