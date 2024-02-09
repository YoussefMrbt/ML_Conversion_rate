
# Machine Learning Challenge: Predicting Newsletter Subscription Conversions

## Overview

This project is centered around the development of a predictive model for determining the likelihood of users subscribing to the www.datascienceweekly.org newsletter. By analyzing user interaction data from the website, the goal is to identify patterns and features that can predict subscription conversions. The project encompasses the entire data science workflow: from exploratory data analysis (EDA) and preprocessing to model training, evaluation, and performance assessment. The challenge emphasizes the use of various machine learning algorithms to achieve the highest possible F1 score, a critical metric for balancing precision and recall in the predictions.

## Dataset

The dataset provided for this challenge is split into two files:

- conversion_data_train.csv: Contains labeled data, including features (user interaction data) and the target variable (whether the user subscribed to the newsletter).
- conversion_data_test.csv: Contains unlabeled data, including only the features. This set is used for making predictions to assess the model's performance.

## Notebook Structure

The project notebook is organized into the following sections:

Importing Libraries: Setup of the Python environment with necessary libraries for data manipulation, visualization, model training, and evaluation.
Exploratory Data Analysis: Initial examination of the data to understand distributions, identify patterns, and spot outliers or missing values.
Preprocessing: Preparation of the data for modeling, including handling missing values, encoding categorical variables, and feature scaling.
Models: Training and optimization of various machine learning models:
Support Vector Machine (SVM)
Random Forest
Decision Tree
Logistic Regression
K-Nearest Neighbors (KNN)
Gradient Boosting
XGBoost

Performance Assessment: Evaluation of each model's performance using the F1 score and accuracy, including the presentation of confusion matrices for a detailed analysis of predictions.

## Goals

The project aims to:

- Conduct a thorough EDA to guide the preprocessing and modeling decisions.
- Train multiple models to predict newsletter subscription conversions effectively.
- Evaluate model performances with a focus on the F1 score to ensure a balanced assessment of precision and recall.

Provide insights into model behaviors and identify key features influencing user decisions to subscribe, thereby offering actionable recommendations to improve conversion rates.

## Deliverables

The deliverable for this project is a comprehensive Jupyter notebook that includes all analyses, model training steps, evaluations, and predictions. Additionally, predictions made on the conversion_data_test.csv file are submitted in a separate CSV file, adhering to the competition's submission format.

## Recommendations

Based on the model's analysis, recommendations will be provided to enhance the newsletter's conversion rate. These insights will focus on understanding user behavior and identifying strategic levers to encourage more subscriptions.
