# Predicting Air Quality with Neural Networks

A deep learning project that predicts the Air Quality Index (AQI) of Indian cities using a Neural Network trained on real air quality data collected across India from 2015 to 2020.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Dependencies](#dependencies)
- [Results](#results)
- [License](#license)
- [Contact](#contact)

## Overview

Air pollution is one of the biggest threats to human health and the environment today. This project uses a Neural Network built with TensorFlow and Keras to predict the Air Quality Index (AQI) based on various pollution parameters like PM2.5, PM10, NO2, CO, SO2, and more.

The model is trained on the Air Quality Data in India (2015 - 2020) dataset which contains city-wise daily air quality readings from multiple cities across India. The goal was to preprocess the data, analyze patterns, and build a model that can accurately predict AQI values.

## Features

- Loads and explores real air quality data from Indian cities (2015-2020)
- Handles missing values by removing incomplete records
- Exploratory Data Analysis (EDA) with interactive visualizations using Plotly
- AQI trend analysis over time and city-wise distribution
- Feature standardization using StandardScaler
- Neural Network model built with TensorFlow and Keras (Dense layers with ReLU activation)
- Model compiled with Adam optimizer and Mean Squared Error loss
- Training and validation loss tracking across 150 epochs
- Predicts AQI for custom user input values

## Project Structure
```
Predicting-Air-Quality-with-Neural-Networks/
│
├── predicting_air_quality.ipynb   # Main Jupyter Notebook
├── dataset/                       # Dataset folder
│   └── city_day.csv
├── model.h5                       # Saved trained model
├── README.md                      # Project documentation
└── requirements.txt               # Dependencies
```

## Installation

1. Clone the repository
```
git clone https://github.com/Vicky-Vrishni/Predicting-Air-Quality-with-Neural-Networks.git
```
2. Navigate to the project folder
```
cd Predicting-Air-Quality-with-Neural-Networks
```
3. Install the required libraries
```
pip install -r requirements.txt
```

## Dependencies

- Python 3.x
- TensorFlow
- Keras
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Plotly
- Jupyter 
## Results

The Neural Network was trained for 150 epochs on the Air Quality Data in India (2015-2020) dataset. The model achieved a Mean Squared Error (MSE) of **444.50** on the test data. The training and validation loss curves showed steady improvement across epochs, confirming that the model learned meaningful patterns from the data.

A sample prediction for custom user input returned a predicted AQI of approximately **197.98**, which closely matched the expected range based on the input pollution parameters.

## Contact

[GitHub](https://github.com/Vicky-Vrishni) | [Email](skvickyyaday942@gmail.com) | [LinkedIn](https://www.linkedin.com/feed/)
