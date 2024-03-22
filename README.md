[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/7lKBcjfN)
# 44-566 machine-learning project
Repo for all project documents

# Traffic Analysis Project

## Overview
This project aims to analyze traffic data using machine learning techniques to understand traffic patterns and predict traffic situations. The project includes several notebooks, each focusing on different aspects of the analysis.

### Notebooks Overview
1. Data Exploration
This notebook explores the dataset containing traffic data, including timestamps, vehicle counts, and traffic situations. It examines the distribution of features, identifies any missing values, and visualizes key insights using plots and graphs.

2. Feature Engineering
In this notebook, we perform feature engineering to extract useful features from the raw data. This includes converting timestamps into numerical features, creating lag features to capture temporal patterns, and encoding categorical variables.

3. Initial Data Preparation
The initial data prep notebook reads, cleans, and prepares the dataset for modeling. It selects relevant features and splits the data into training and testing sets.

4. Decision Tree Classifier
The decision tree classifier notebook implements a basic classification model using a decision tree algorithm. It evaluates the model's performance using metrics such as precision, recall, and F1-score.

5. Support Vector Machine (SVM) Classifier
This notebook explores the use of SVM as an alternative classifier to improve the model's performance. It compares the results of SVM with the decision tree classifier and discusses any improvements.

6. Model Evaluation and Comparison
In this notebook, we perform a final evaluation of the models using the test set. We compare the performance of the decision tree classifier and SVM, analyzing their respective strengths and weaknesses.

### Important Results
The decision tree classifier achieved an overall accuracy of 0.75, with precision and recall scores varying across different traffic situations.
SVM outperformed the decision tree classifier with an accuracy of 0.80, indicating its effectiveness in handling non-linear data.
Feature engineering played a crucial role in improving model performance by extracting relevant features and encoding categorical variables.