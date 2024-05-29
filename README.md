# Earnings Prediction Project
## Overview

This GitHub repository contains the code and documentation for a project focused on predicting earnings in the USA based on the National Longitudinal Survey of Youth 1997-2011 dataset. The primary objective of this project was to develop a robust predictive model using XGBoost Regression, with additional efforts invested in feature engineering to enhance model performance.

## Dataset

The project utilizes the National Longitudinal Survey of Youth 1997-2011 dataset, which provides a rich set of features related to individuals' characteristics, education, and other relevant factors. The dataset serves as the foundation for training and evaluating the XGBoost Regression model.

## Code Structure

  NLSY97_Variable_Names_and_Descriptions.csv/: Contains that dataset variables' names and descriptions.
  
  NLSY97_subset.csv/: Contains the dataset used for training and testing the model.
  
  Determinants of Earnings.ipynb/: Jupyter notebooks used for data exploration, feature engineering, model training, and evaluation.

## Feature Engineering

To improve the model's predictive performance, various feature engineering techniques were applied. These techniques include:

  Handling missing data.
  
  Encoding categorical variables.
  
  Creating new relevant features.
  
  Scaling and transforming numerical features.
  
  Feature Selection

## Model

The XGBoost Regression model was chosen for its ability to handle complex relationships in the data and its robustness in predicting numerical outcomes. The model was trained on the preprocessed dataset, and hyperparameter tuning may have been performed to optimize its performance.
Usage

  ### Clone the repository:

  ### bash

    git clone https://github.com/Stephen-Echessa/USA-Earnings-Prediction.git

## Results

Details on the model's performance, evaluation metrics, and insights derived from the analysis can be found in the Determinants of Earnings.ipynb notebook.

Feel free to explore, adapt, and contribute to this project! If you have any questions or suggestions, please open an issue or reach out to stevechesa@gmail.com.
