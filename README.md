# House Prices Prediction 

This repository contains a solution for the "House Prices: Advanced Regression Techniques" competition on Kaggle. The goal of the competition is to predict house prices based on a given dataset. The solution utilizes various machine learning models and includes data preprocessing, feature engineering, model training, and prediction.

Dataset taken from [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

## Code Overview

The code is written in Python and uses popular libraries for data manipulation, visualization, and modeling, including Pandas, Matplotlib, Seaborn, and scikit-learn. Here's an overview of the major steps in the code:

- **Importing Libraries:** Necessary libraries are imported to facilitate data handling, visualization, and modeling.
- **Data Loading:** The training and test datasets are read from CSV files.
- **Data Exploration:** Initial exploration of the training dataset is performed, including displaying information, summary statistics, and the first few rows of the data.
- **Handling Missing Values:** Missing values in the dataset are addressed by either filling them with appropriate values or dropping columns containing missing data.
- **Feature Engineering:** Skewed numerical columns are log-transformed, and categorical columns are converted into dummy variables to prepare the data for modeling.
- **Model Training:** Several regression models, including Ridge, Lasso, LassoCV, XGBoost, and Random Forest, are trained on the preprocessed data using appropriate training techniques and parameter settings.
- **Model Evaluation:** The trained models' performance is evaluated using the root mean squared logarithmic error (RMSLE) metric.
- **Feature Selection:** Top features are selected based on the models' coefficients to improve model performance and reduce dimensionality.
- **Prediction:** The selected models are used to make predictions on the test dataset, and an ensemble approach is applied to combine the predictions.
- **Submission:** A submission file in CSV format is generated with the predicted house prices for submission to the competition.

## Usage

To use this code, follow these steps:

- Ensure that Python is installed on your system along with the required libraries mentioned in the code.
- Download the training and test datasets from the Kaggle competition page.
- Place the CSV files in the appropriate directory or update the file paths in the code accordingly.
- Execute the code to preprocess the data, train the models, and make predictions
