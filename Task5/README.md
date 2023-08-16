# Credit Card Fraud Detection using PySpark

Data Set Link : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

This GitHub repository contains code for building a Credit Card Fraud Detection model using Apache Spark in a Google Colab environment. The provided code demonstrates the process of setting up Spark, loading and preprocessing the dataset, training a fraud detection model, and evaluating its performance metrics.

# Table of Contents
Introduction
Setup
Data Loading and Preprocessing
Model Training
Model Evaluation
Results
License
# Introduction
Credit card fraud detection is a critical application in the finance industry. This repository showcases how to build and evaluate a fraud detection model using Apache Spark, a powerful distributed computing framework.

# Setup
To run the code in this repository, follow these steps:

Open a Google Colab notebook.

Copy and paste the provided code into a code cell.

Run the code cell to set up Apache Spark, load and preprocess the dataset, train a fraud detection model, and evaluate its performance.

# Data Loading and Preprocessing
The code includes the following steps for data loading and preprocessing:

Loading the credit card dataset using Spark DataFrame.
Creating a vector of features using the VectorAssembler transformation.
# Model Training
The code demonstrates how to train a Random Forest classifier for fraud detection:

Initializing a Random Forest classifier.
Fitting the model on the training dataset.
# Model Evaluation
The model's performance is evaluated using several metrics:

Accuracy: The proportion of correctly predicted instances.
Precision: The ratio of correctly predicted positive observations to the total predicted positives.
Recall: The ratio of correctly predicted positive observations to the actual positives.
F1 Score: The weighted average of precision and recall.
# Results
After running the code, the following evaluation results are obtained:

Precision: 0.9991815467526846
Recall: 0.9992286250241055
F1 Score: 0.999189734425383
These high-performance metrics indicate the effectiveness of the trained model in detecting credit card fraud.

# License
This code is provided under the MIT License.

Feel free to modify, adapt, and utilize this code for your own projects. If you encounter any issues or have questions, please create an issue in this repository.

Happy Fraud Detection!
