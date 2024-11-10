### Boston House Pricing Prediction

### Software And Tools Requirements


### Table of Contents

[Overview](#Overview)

[Dataset](#Dataset)

[Installation](#Installation)

[Usage](#Usage)

[Model](#Model)

[Results](#Results)

[Software And Tools Requirements](#Software)

## Overview

This project aims to predict house prices in Boston using various machine learning algorithms. The dataset used is the famous Boston Housing Dataset, which includes features like crime rate, number of rooms, and distance to employment centers.
### Dataset

The dataset contains 506 samples with 13 features each. The target variable is the median value of owner-occupied homes in $1000's. The features are:

  CRIM: per capita crime rate by town
    ZN: proportion of residential land zoned for lots over 25,000 sq. ft.
    INDUS: proportion of non-retail business acres per town
    CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
    NOX: nitric oxides concentration (parts per 10 million)
    RM: average number of rooms per dwelling
    AGE: proportion of owner-occupied units built prior to 1940
    DIS: weighted distances to five Boston employment centers
    RAD: index of accessibility to radial highways
    TAX: full-value property tax rate per $10,000
    PTRATIO: pupil-teacher ratio by town
    B: 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents by town
    LSTAT: % lower status of the population

### Installation

* Clone the repository:
  
          git clone https://github.com/Reetesh9794/bostonhousepricing.git

* Create and activate a virtual environment:

conda create -p venv python==3.7 -y

* Install the required packages:

pip install -r requirements.txt

### Usage

* Exploratory Data Analysis (EDA):

    Navigate to the notebooks directory and open eda.ipynb to explore the dataset and visualize the features.

* Model Training:

    Run the train_model.py script to train the models:

       python train_model.py

* Prediction:

    Use the predict.py script to make predictions on new data:

       python predict.py --input data/new_data.csv --output data/predictions.csv

### Model

Various regression models are used in this project:

  Linear Regression
  Ridge Regression
  Lasso Regression

Each model is evaluated based on metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared score.

### Results

The performance of the models can be found in the results directory. The model_comparison.csv file contains the evaluation metrics for each model.


## Software

    Githubs Account
    Vs Code IDE
    HerokuAccount
    GitCLI

