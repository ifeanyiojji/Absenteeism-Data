# Predicting Absenteeism Using Machine Learning
This repository contains a Python-based machine learning project designed to predict absenteeism probabilities in the HR department. By leveraging a machine learning model and preprocessing techniques, this project enables HR teams to anticipate and mitigate lateness issues.

## Features
Custom Data Preprocessing: A custom scaler and data transformation to standardize features.
Reason Categorization: Absenteeism reasons categorized into four groups to streamline analysis.
Prediction Outputs:
  Probabilities of absenteeism.
  Binary predictions for absenteeism classification.
  Scalable Design: The project is structured to easily integrate new datasets.


## Installation
1. Clone the repository:
  git clone https://github.com/yourusername/absenteeism-prediction.git
2. Ensure you have the model (model) and scaler (scaler) files saved in the project directory.

## Usage
1. Load Data: Prepare a CSV file with the required features, following the expected format.
2. Run the Model:
  Use the absenteeism_model class to load and preprocess your data.
  Predict absenteeism probabilities and classifications.
3. Output: The processed data includes the probabilities and binary predictions appended to the original dataset.


## Files
absenteeism_module.py: Main module for data preprocessing and predictions.
model: Pre-trained machine learning model (saved as a binary file).
scaler: Pre-trained scaler for feature normalization.


## Data Format
Your input CSV file should include the following columns:
ID
Reason for Absence
Date
Transportation Expense
Distance to Work
Age
Daily Work Load Average
Body Mass Index
Education
Children
Pet
