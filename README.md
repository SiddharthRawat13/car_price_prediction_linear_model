# Car_price_prediction_linear_model
Car Price Prediction Model
This repository contains a machine learning model designed to predict car prices based on various features such as the year, mileage, engine size, and more. The model utilizes linear regression and is deployed with a user-friendly interface using Gradio.

## Overview
The aim of this project is to help users estimate the price of a car based on its specifications. The model takes into account several features that are commonly considered when determining the price of a car.

## Features
Linear Regression Model: The machine learning model is trained using scikit-learn's LinearRegression class to predict car prices.

User-Friendly Interface: The model is accessible through a web-based interface implemented using Gradio. This makes it easy for users to input car details and get instant price predictions.

## Dataset
The dataset used to train the model is sourced from Auto Car Trader and is available in the cleaned_auto_car_trader1.csv file. The dataset includes various features such as:

Year,
Mileage,
Engine type,
Transmission type,
Engine size,
City mileage,
Highway mileage,
Gear,
Cylinder,


## Installation To use the model and interface, follow these steps:

Clone the Repository:

bash
Copy code
git clone https://github.com/SiddharthRawat13/car_price_prediction_linear_model
Navigate to the Repository Directory:

bash
Copy code
cd car-price-prediction
Install Required Libraries:

bash
Copy code
pip install pandas, numpy, scikit-learn and gradio
### Usage
Training the Model
The model is trained using the Car_Price_Prediction_Model.ipynb Jupyter notebook. You can explore this notebook to understand the data preprocessing and model training steps.

Predicting Car Price
To predict the price of a car:

Launch the Gradio Interface:

bash
Copy code
python gradio_interface.py

### Input Car Details:

Year,
Mileage,
Engine size,
Cylinder,
Engine type,
City mileage,
Highway mileage,
Gear,
Transmission type,
Get Price Prediction:
Click on the "Submit" button to get the predicted price.
