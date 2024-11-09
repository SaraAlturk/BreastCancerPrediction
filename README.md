# BreastCancerPrediction

## Dataset Description

The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) dataset, a commonly used dataset for binary classification tasks in medical research. 
This dataset consists of 569 samples of breast tissue biopsies, each classified as either Malignant (M) or Benign (B).

https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data/data

**Dataset Details**
Features: 30 numeric features, representing various characteristics of cell nuclei in images of fine needle aspirate (FNA) biopsies of breast masses. 

These include: Mean, standard error, and "worst" values (i.e., largest values) for various properties of the cell nuclei, such as radius, texture, perimeter, area, smoothness, compactness, concavity, symmetry, and fractal dimension.

Target: A binary label indicating the diagnosis of each sample:

`Malignant (M)`: 1

`Benign (B)`: 0

The data was preprocessed with feature scaling to ensure that each feature contributes equally to the model's learning process.


## First Notebook Overview

This notebook demonstrates the application and comparison of three machine learning models—Logistic Regression, Support Vector Machine (SVM), and Perceptron—on the Breast Cancer Prediction task. 

The goal is to classify breast cancer as either Malignant or Benign based on a range of features derived from cell nucleus measurements.

**Model Implementations:**

Logistic Regression: A linear model used for binary classification tasks, which outputs probabilistic predictions.

Support Vector Machine (SVM): A classifier that finds the hyperplane maximizing the margin between the two classes, with optional kernel support.

Perceptron: A simple linear classifier that updates its weights based on misclassifications, typically used for linearly separable data.
