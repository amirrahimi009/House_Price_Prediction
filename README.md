# House Price Prediction

A machine learning project for predicting house prices using linear regression and synthetic housing data.

## Project Overview

This project uses machine learning to predict the price of a house based on several features.

The model uses `SGDRegressor` from `scikit-learn`.

The dataset is synthetic and was created for educational purposes.

## Features

The model uses six features:

* House size in square meters
* Number of bedrooms
* Number of floors
* House age
* Parking availability
* Distance from the city center

## Machine Learning Process

The project follows these steps:

1. Create the dataset
2. Split the data into training and testing sets
3. Scale the features using `StandardScaler`
4. Train the model using `SGDRegressor`
5. Evaluate the model
6. Use the trained model to predict the price of a new house

## Model

The model used in this project is:

`SGDRegressor`

Feature scaling is performed using:

`StandardScaler`

## Evaluation

The model is evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

These metrics are used to measure the difference between the predicted prices and the actual prices.

## Example Input

The program asks the user for:

```text
House size
Number of bedrooms
Number of floors
House age
Parking availability
Distance from city center
```

The model then predicts the estimated house price in million Toman.

## Dataset

The dataset used in this project is synthetic.

The values were created for learning and demonstrating a machine learning regression workflow.

Therefore, the model should not be used to estimate real-world housing prices.

## Technologies

* Python
* NumPy
* Scikit-learn
* Machine Learning
* Linear Regression
* Gradient Descent

## Project Structure

```text
house-price-prediction/
│
├── house_price_prediction.py
├── requirements.txt
├── README.md
└── .gitignore
```

## Future Improvements

Possible improvements for this project include:

* Using a real housing dataset
* Increasing the number of training examples
* Adding more relevant features
* Testing other regression algorithms
* Improving model evaluation
* Deploying the model as a web application

## Author

Amir Rahimi
