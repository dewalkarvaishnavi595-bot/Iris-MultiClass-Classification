# Iris-MultiClass-Classification


Multi-Class Benchmark Classification Pipeline

Project Overview

This project implements an end-to-end multiclass classification pipeline using the Iris dataset and Scikit-Learn.

Two machine learning models are trained and compared:

Logistic Regression

Decision Tree Classifier

The models are evaluated using accuracy, precision, recall, F1-score, confusion matrices, and ROC curves.

Dataset

The Iris dataset contains 150 samples belonging to three classes:

Setosa

Versicolor

Virginica

Features

Sepal Length

Sepal Width

Petal Length

Petal Width

Technologies Used

Python

Pandas

NumPy

Scikit-Learn

Matplotlib

Seaborn

Jupyter Notebook

Project Workflow

Load the Iris dataset

Explore and inspect the data

Check missing values

Perform exploratory data analysis

Generate pairplot

Split data into 80% training and 20% testing

Apply StandardScaler

Train Logistic Regression

Train Decision Tree

Generate predictions

Calculate accuracy, precision, recall, and F1-score

Generate confusion matrices

Generate ROC curves

Compare model performance

Visualize the decision boundary

Models

Logistic Regression

Logistic Regression is used as a baseline classification model for predicting Iris species.

Decision Tree

Decision Tree Classifier is used as a second model for comparing classification performance.

Evaluation Metrics

The models are evaluated using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

ROC Curve

AUC

Results

The performance of both models is presented in the Jupyter Notebook using evaluation metrics, confusion matrices, ROC curves, and comparison graphs.

How to Run

Install the required libraries:

pip install -r requirements.txt

Open the notebook:

jupyter notebook Iris_MultiClass_Classification.ipynb

Run all cells in the notebook to reproduce the results.

Project Structure

Iris-MultiClass-Classification/
│
├── Iris_MultiClass_Classification.ipynb
├── README.md
├── requirements.txt
└── outputs/
    ├── pairplot.png
    ├── confusion_matrix_logistic.png
    ├── confusion_matrix_decision_tree.png
    ├── model_comparison.png
    ├── decision_boundary.png
    └── roc_curve.png

