Predictive Maintenance Machine Learning Project
📘 Overview

This project demonstrates a complete Predictive Maintenance machine learning workflow designed for real-world industrial applications. It simulates sensor data from industrial machinery and uses machine learning to predict whether a component is likely to fail.

This type of project is widely used in manufacturing, mining, aviation, logistics, and utilities — making it an excellent addition to a professional data science or machine learning portfolio.

🚀 Project Objectives

Build a realistic predictive maintenance dataset using synthetic sensor data.

Train and evaluate a machine learning model to predict component failures.

Demonstrate a full end‑to‑end ML workflow:

Data preprocessing

Train/test splitting

Feature scaling

Model training and evaluation

Practical prediction on new sensor inputs

Provide a clean, professional notebook suitable for portfolio use.

📊 Dataset Description

The dataset contains 3,000 machine sensor readings with the following features:

Feature	Description
temperature	Operating temperature of the machine
vibration	Vibration intensity (higher can indicate mechanical issues)
pressure	Internal pressure levels
runtime_hours	Total operating hours since last service
humidity	Environmental moisture around the machine
component_failure (target)	1 = failure, 0 = normal operation

The target variable is generated realistically: machines under extreme conditions have a higher chance of failure.

Dataset file: predictive_maintenance_dataset.csv

🧠 Machine Learning Approach

A Random Forest Classifier is used because it:

Handles nonlinear relationships

Works well with sensor-based data

Provides robust performance

Is interpretable through feature importance

Preprocessing Steps

Train-test split (80/20)

Standard scaling of numeric features

Random Forest model (200 trees)

Evaluation Metrics

The notebook outputs:

Classification Report (precision, recall, F1-score)

ROC-AUC Score

ROC Curve Visualization

These metrics help assess how well the model distinguishes between failure and non-failure cases.

🧪 Testing New Sensor Readings

The project includes code that allows you to feed new, unseen sensor data into the trained model.

Example input:

ew_reading = {
    "temperature": 92,
    "vibration": 4.5,
    "pressure": 36,
    "runtime_hours": 4200,
    "humidity": 60
}

The notebook outputs:

Prediction: FAILURE
Failure Probability: 0.87

You can adapt this logic to build:

Real-time monitoring systems

Dashboards

API endpoints
