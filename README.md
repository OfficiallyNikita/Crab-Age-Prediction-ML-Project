# Crab Age Prediction - Machine Learning Project 🦀
A machine learning project to predict the age of crabs using regression models, with Python-based data preprocessing, model evaluation, and result generation.

## Project Overview
This project aims to predict the age of crabs using various machine learning regression models. By leveraging Python libraries like pandas, scikit-learn, and Gradient Boosting Regressor, the dataset was processed, evaluated, and the best model was selected for predictions.

## Problem Statement
The objective is to develop a machine learning model that can accurately predict the crab's age based on physical attributes like Length, Weight, and Height. The dataset contains labeled data for training and unseen test data for final predictions.

## Technologies and Tools Used
Python : Pandas, scikit-learn, Matplotlib, NumPy, Gradient Boosting, Random Forest, Linear Regression <br>
Google Colab

## Dataset Description
--> Training Dataset (train.csv) 
Contains labeled data with the following features:<br>
Sex (M/F/I), 
Length, 
Diameter, 
Height, 
Weight, Shucked Weight, Viscera Weight, Shell Weight, 
Age (Target variable)
<br>
-->Test Dataset (testData.xlsx)
Contains unseen data without the Age column, used for final model predictions.

## Model Evaluation
Multiple machine learning models were trained and evaluated using the following metrics:
<br>
--> Best Performing Model:
Gradient Boosting Regressor 🏆

## Project Files
train.csv: Training dataset.<br>
testData.xlsx: Unseen test dataset.<br>
result.csv: Final predictions on the test data.<br>
Crab_Age_Prediction.ipynb: Python notebook containing the entire code (EDA, data preprocessing, model training, evaluation, and predictions).<br>
gradient_boosting_model.pkl: Saved model for future predictions.


## Results and Output
The final predictions on unseen test data are saved in result.csv.

## Future Improvements
Tune hyperparameters for better performance.<br>
Use additional models like XGBoost or LightGBM for comparison.<br>
Add more visualizations to explore feature importance.<br>

