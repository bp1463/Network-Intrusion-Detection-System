# Network-Intrusion-Detection-System

# Overview

This project implements an Intrusion Detection System (IDS) using a Random Forest Classifier to detect and classify network anomalies and potential security breaches. The model is trained on a dataset of network traffic data, with the goal of identifying abnormal behavior that could indicate an intrusion.

# Features

- Data Preprocessing: Handles missing values, encodes categorical variables, and splits data into training and testing sets.
- Model Training: Uses RandomForestClassifier for training and evaluation, with hyperparameter tuning to optimize performance.
- Evaluation Metrics: Provides detailed evaluation using accuracy, confusion matrix, and classification report.

# Libraries

1. Pandas

2. Scikit-learn (sklearn)

3. Kaggle API

# Usage

1. Prepare the Data:
    - Connect dataset from kaggle.

2. Run the Notebook:
    - Open the Jupyter Notebook `Intrusion_Detection_System.ipynb` and run the cells sequentially to execute the entire workflow.

3. Model Training and Evaluation:
    - The notebook includes steps for preprocessing the data, training the Random Forest model, and evaluating its performance.


## Evaluation

The performance of the IDS is evaluated using the following metrics:
- Accuracy: 99.82%
- Confusion Matrix: Displays the model's performance on different classes.
- Classification Report: Provides precision, recall, and F1-score for each class.