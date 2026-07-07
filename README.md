# Breast Cancer Classification Using Logistic Regression

A binary classification model implemented from scratch using NumPy to classify breast tumors as malignant or benign.

## Overview

This project uses the Wisconsin Diagnostic Breast Cancer dataset and implements the main components of logistic regression, including:

- Z-score feature normalization
- Sigmoid activation function
- Logistic loss computation
- Gradient calculation
- L2 regularization
- Batch gradient descent
- Binary classification using a probability threshold
- Model evaluation and visualization

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Results

The model achieved:

- **Accuracy:** 97.4%
- **Precision:** 98.6%
- **Recall:** 97.2%
- **F1 Score:** 97.9%
- **Malignant Recall:** 97.6%
- **AUC Score:** 0.995

The model correctly identified **41 out of 42 malignant cases** in the test set.

## Course Reference

The core logistic regression concepts and functions used in this project were learned through Andrew Ng's **Supervised Machine Learning: Regression and Classification** course on Coursera.

I adapted these concepts to build and evaluate a complete binary classification pipeline using the Wisconsin Diagnostic Breast Cancer dataset.

## Note

This project is intended for educational purposes and demonstrates the implementation of logistic regression from scratch. It is not intended for clinical or medical use.
