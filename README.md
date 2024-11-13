Sonar Data Classification
Overview
This project uses Logistic Regression to classify sonar data and predict whether an object is a rock or a mine based on sonar readings.

Requirements
Python 3.x
NumPy
Pandas
scikit-learn

Code Breakdown
Load Data: The dataset is loaded into sonar_data.
Preprocess: Split data into features (X) and labels (Y).
Train Model: Train a Logistic Regression model using the training data.
Evaluate: Calculate accuracy on both training and testing data.
Predict: Classify a new sonar reading as a rock or mine.

Output
Accuracy on training data: 83%
Accuracy on test data: 76%
