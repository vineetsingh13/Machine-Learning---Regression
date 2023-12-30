# Machine-Learning---Regression
## CO2 Emission Prediction Using Linear Regression
This repository contains code for predicting CO2 emissions of vehicles using simple linear regression and multiple linear regression. The dataset used for this analysis includes information about various car models, their specifications, and CO2 emissions.

## Dataset
The dataset used is a collection of vehicle data for the year 2014. Each record in the dataset represents a specific car model and includes the following information:

- Model Year
- Make (manufacturer)
- Model
- Vehicle Class
= Engine Size
- Cylinders
- Transmission Type
- Fuel Type
- Fuel Consumption in City (L/100km)
- Fuel Consumption on Highway (L/100km)
- Combined Fuel Consumption (L/100km)
- Combined Fuel Consumption (MPG)
- CO2 Emissions

# Linear Regression Models
## Simple Linear Regression
The simple linear regression models have been implemented using three independent variables separately:

1. Engine Size
2. Cylinders
3. Combined Fuel Consumption
Each variable is used individually as the predictor, and CO2 emissions are the dependent variable.

## Multiple Linear Regression
The multiple linear regression model is implemented using three independent variables together:

1. Engine Size
2. Cylinders
3. Combined Fuel Consumption
In this case, all three variables are used simultaneously as predictors, and CO2 emissions are the dependent variable.

## Code Execution Environment
The code has been implemented using Python and executed in Google Colaboratory. Google Colaboratory provides a free and convenient platform for running Python code in a Jupyter notebook environment with access to GPU.

## Files in the repository

- simpleLinearRegression.ipynb: Jupyter notebook containing the code for simple linear regression.
- MultipleLinearRegression.ipynb: Jupyter notebook containing the code for multiple linear regression.
- FuelConsumptionCo2.csv: The dataset used for training and testing the models.
README.md: This readme file.
