# HumanResource_Analysis

📊 HR Analytics Using Naive Bayes (PySpark)

A Machine Learning project that predicts employee attrition using PySpark (Apache Spark’s Python API) and visualizes HR insights through a detailed dashboard built with Matplotlib and Seaborn.

🚀 Project Overview

This project applies Naive Bayes classification on a real-world HR dataset to analyze and predict which employees are likely to leave the organization. The primary goal is to help HR departments identify risk factors affecting attrition and take data-driven decisions to improve employee retention.

Apache Spark (PySpark) is used to handle large-scale data processing, while visualization libraries like Matplotlib and Seaborn generate a comprehensive analytics dashboard.

🎯 Objectives

Preprocess HR employee data using PySpark

Convert categorical features into numerical form using StringIndexer

Combine features for model training using VectorAssembler

Train a Multinomial Naive Bayes classifier

Evaluate model performance using accuracy and a confusion matrix

Create a multi-graph dashboard to understand attrition patterns visually

Identify key factors contributing to employee attrition

📁 Dataset

File: HR_comma_sep.csv
Contains employee-level information such as:

Satisfaction level

Last evaluation score

Number of projects

Monthly working hours

Years spent in the company

Work accidents

Promotion history

Salary category

Department

Attrition status (target label)

🧠 Machine Learning Model

This project uses Naive Bayes (Multinomial) from Spark MLlib.

Why Naive Bayes?

Works well with categorical data

Fast and scalable (ideal for Spark)

High interpretability

Good baseline model for classification problems

⚙️ Tech Stack
Tool / Library	Purpose
PySpark	Data processing & ML model training
Spark MLlib	Machine Learning pipeline
Matplotlib	Data visualization
Seaborn	Statistical plots
Pandas	Data manipulation for visualization
Python 3.12/3.13 Fix	Compatibility for distutils removal
📈 Dashboard Visualizations

The dashboard includes 6 analytical plots:

Employee Attrition Distribution

Salary Level vs Attrition

Department-wise Attrition

Satisfaction Level Distribution by Attrition

Actual vs Predicted Employee Attrition

Feature Correlation Heatmap

These plots reveal the key drivers of attrition and give a visual overview of the dataset.

🧪 Model Evaluation

Accuracy: ~76.9%

Confusion Matrix: Used to evaluate correct vs incorrect predictions

Model performed well for predicting employees who stay, moderate performance for predicting employees who leave (class imbalance).

📦 Features

End-to-end ML pipeline using PySpark

Preprocessing of categorical + numerical features

Model training, testing, and evaluation

Professional HR Analytics dashboard

Fully documented and readable code
