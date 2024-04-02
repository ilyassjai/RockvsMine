
# Rock vs. Mine Prediction with SONAR Data

## Overview
This repository contains a Python-based system that uses SONAR data to predict whether an object is either a rock or a mine. The prediction model is based on Logistic Regression.

## Files
- `Notes.ipynb`: This Jupyter Notebook contains the code for data preprocessing, model training, and evaluation.
- `Copyofsonardata.csv`: This is the dataset used for training and testing the model.

## Dependencies
Ensure you have the following Python libraries installed:
- pandas
- numpy
- scikit-learn



## Usage
1. Load the dataset: The dataset is loaded from the `sonar_data.csv` file.
2. Preprocess the data: The data is split into features (X) and target labels (Y). The target labels are what we want to predict (either 'R' for Rock or 'M' for Mine).
3. Split the data: The data is split into training and testing sets. 80% of the data is used for training the model and the remaining 20% is used for testing its performance.
4. Train the model: A Logistic Regression model is trained on the training data.
5. Evaluate the model: The model's performance is evaluated on the testing data.

## Results
The model achieved an accuracy of approximately 84.33% on the training data and 69.04% on the test data.

## Future Work
Improvements can be made by experimenting with different models, tuning the hyperparameters of the model, or using more advanced techniques for preprocessing the data.
