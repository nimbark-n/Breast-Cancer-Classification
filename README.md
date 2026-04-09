# Breast-Cancer-Classification
Breast Cancer Classification using Machine Learning
Overview

This project presents an end-to-end machine learning pipeline to classify breast tumors as malignant or benign using structured clinical data. The objective is to demonstrate how fundamental machine learning techniques can be applied to real-world healthcare problems with strong predictive performance.

Problem Statement

Early and accurate detection of breast cancer is critical for effective treatment. This project builds a classification model that predicts whether a tumor is malignant or benign based on diagnostic features.

Dataset

The dataset used is the Breast Cancer Wisconsin dataset, available through scikit-learn.

Number of samples: 569
Number of features: 30 numerical features
Target classes:
0: Malignant
1: Benign

The features represent measurements computed from digitized images of breast mass samples.

Methodology
Data Preparation

The dataset is loaded from scikit-learn and converted into a structured DataFrame. Basic checks are performed to ensure data quality, including validation for missing values and consistency.

Exploratory Data Analysis

The distribution of classes is examined to understand balance in the dataset. Feature patterns are explored by comparing mean values across classes to identify distinguishing characteristics.

Train-Test Split

The dataset is divided into training and testing subsets to evaluate model generalization.

Model Training

A Logistic Regression model is trained on the dataset due to its interpretability and strong baseline performance for binary classification tasks.

Model Evaluation

Model performance is evaluated using accuracy on the test dataset.

Results

The Logistic Regression model achieves high accuracy on the test data, indicating that the dataset is well-structured and separable using linear decision boundaries. This highlights the effectiveness of simple models when features are informative.

Tech Stack
Python
NumPy
Pandas
Scikit-learn
How to Run
Install required dependencies:
pip install numpy pandas scikit-learn
Launch Jupyter Notebook:
jupyter notebook Breast_Cancer_Classification_using_ML.ipynb
Run all cells to reproduce results.
Key Takeaways

This project demonstrates how to structure a complete machine learning workflow, including data preparation, exploratory analysis, model building, and evaluation. It also shows that interpretable models such as Logistic Regression can perform effectively on biomedical datasets.

Future Work

Future improvements can include experimenting with more complex models such as Random Forest, Support Vector Machines, or Gradient Boosting methods. Additional steps such as feature selection, hyperparameter tuning, and cross-validation can further enhance performance. The project can also be extended into a deployable application for real-world use.
