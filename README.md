# Diabetes Prediction Using Support Vector Machine (SVM)

## Overview
This project aims to predict the likelihood of diabetes in patients using machine learning techniques, specifically utilizing a Support Vector Machine (SVM) with a linear kernel. The dataset used is the PIMA Diabetes Dataset, containing health-related features such as glucose level, blood pressure, BMI, age, and more.

## Prerequisites
Libraries used:
- pandas
- numpy
- scikit-learn

## Features
- **Data Preprocessing**: The dataset is standardized using StandardScaler to ensure all features have a similar scale. This is crucial for algorithms like SVM, which are sensitive to feature scaling.
- **Model Training**: A Support Vector Machine (SVM) is trained on the dataset to classify patients as diabetic or non-diabetic. The linear kernel is chosen for simplicity and efficiency.
- **Evaluation**: Model accuracy is calculated for both training and test datasets.The model's performance is measured using accuracy metrics, which give insight into how well the model predicts both training and test data.
