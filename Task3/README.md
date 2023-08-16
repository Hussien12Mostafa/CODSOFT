# Iris Flower Classification

This GitHub repository contains code for performing classification on the Iris flower dataset using two different machine learning algorithms: Logistic Regression and Support Vector Machine (SVM). The provided code demonstrates data loading, preprocessing, model training, and evaluation.

# Table of Contents
Introduction
Dataset
Setup
Model Training and Evaluation
Results
License
# Introduction
The Iris flower dataset is a popular dataset for practicing classification algorithms. In this repository, we use Logistic Regression and Support Vector Machine to classify the different species of Iris flowers based on their features.

# Dataset
The Iris dataset contains measurements of four features (sepal length, sepal width, petal length, and petal width) for three different species of Iris flowers (Iris setosa, Iris versicolor, and Iris virginica). The goal is to classify the species based on these features.

# Setup
To run the code in this repository, follow these steps:

Make sure you have Python and the necessary libraries installed (NumPy, pandas, scikit-learn, Matplotlib, and Seaborn).
Download the IRIS.csv dataset and ensure it is in the same directory as the code.
Open a Python environment or Jupyter Notebook and copy the provided code into a code cell.
# Model Training and Evaluation
The provided code performs the following steps:

Load the Iris dataset using pandas.
Visualize the distribution of species using a pie chart.
Split the dataset into training and testing sets.
Train a Logistic Regression model and evaluate its performance on the training and testing sets using classification reports.
Train a Support Vector Machine (SVM) model and evaluate its performance on the testing set using a classification report.
# Results
The code provides classification reports for both the Logistic Regression and SVM models. These reports include precision, recall, and F1-score for each class, as well as overall accuracy and macro/micro averages.

Logistic Regression Results:
Precision	Recall	F1-Score	Support
Iris-setosa	1.00	1.00	1.00
Iris-versicolor	0.88	1.00	0.93
Iris-virginica	1.00	0.89	0.94
Accuracy			0.97
SVM Results:
Precision	Recall	F1-Score	Support
Iris-setosa	1.00	1.00	1.00
Iris-versicolor	0.98	0.95	0.96
Iris-virginica	0.95	0.98	0.96
Accuracy			0.97
# License
This code is provided under the MIT License.

Feel free to modify, experiment, and build upon this code for your own classification tasks. If you encounter any issues or have questions, please create an issue in this repository.

Happy Classifying!