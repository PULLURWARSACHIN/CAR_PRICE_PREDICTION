#TECHNOLOGY USED

![WhatsApp Image 2023-09-15 at 2 10 52 PM](https://github.com/PULLURWARSACHIN/CAR_PRICE_PREDICTION/assets/105495917/8e544b20-9816-4d75-ba91-ea36f3d84ee8)


# Car Price Prediction Project

This project aims to predict car prices based on various features using machine learning techniques. The model is trained on a dataset containing information about different cars and their respective prices.

## Table of Contents

- [Introduction](#Introduction)
- [Features](#Features)
- [Installation](#Installation)
- [Usage](#Usage)
- [Model Training](#Model-training)
- [Results](#Results)
- [Contributing](#Contributing)
- [Conclusin](#Conclusin)

## Introduction

Car price prediction is a common problem in the field of data science and machine learning. This project uses a dataset containing features related to cars, such as mileage, horsepower, model year, etc., to predict their prices.



## Features

The dataset contains the following features:

- Mileage
- Make
- Model 
- Fuel
- Gear
- Offer type
- Price
- Hp
- Year

## Installation

2. Install the required dependencies using pip:
- pip install numpy
- pip install pandas
- pip install matplotlib
- pip install sklearn

## Usage

To use the car price prediction model, follow these steps:

1. Prepare your input data in the same format as the dataset, including relevant features.

2. Use the trained model to make predictions on the input data.

Example usage:
   ```python
   from car_price_prediction_model import predict_price

   input_data = {
       "mileage": 2350000,
       "make": BMW,
       "model": 316,
       "fuel": "Disel",
       "gear": "Manual",
       "offertype": "used",
       "price": 6800,
       "hp": 126,
       "year": 2011,
   }

   predicted_price = predict_price(input_data)
   print("Predicted Price:", predicted_price)
   ```

## Model Training

Details about the model training process, including data preprocessing, model selection, hyperparameters, and evaluation, can be found in the `model_training.ipynb` notebook.

## Results

The model achieved a certain 88% accuracy and performance.

## Contributing

If you'd like to contribute to this project, please follow the standard GitHub workflow: Fork, make changes, and submit a pull request. We welcome contributions!

## Conclusion

<img width="1440" alt="Screenshot 2023-09-15 at 2 14 09 PM" src="https://github.com/PULLURWARSACHIN/CAR_PRICE_PREDICTION/assets/105495917/e16fa72b-b8c3-4327-9869-436267db0e84">

##

