# Car Selling Price Predictor

This project aims to predict the selling price of cars based on various features using machine learning techniques. The dataset used contains information such as the year of manufacture, kilometers driven, fuel type, seller type, transmission type, owner history, mileage, engine capacity, maximum power, torque, and number of seats.

## Exploratory Data Analysis (EDA)

The initial analysis includes:

- Checking dataset dimensions and null values.
- Extracting RPM from torque values.
- Converting categorical data into numerical format.
- Visualizing correlations among features using a heatmap.

## Model Building

The predictive model is built using Random Forest Regressor and Linear Regression algorithms. Key steps include:

- Preprocessing data by handling categorical variables and splitting into training and testing sets.
- Training the models.
- Evaluating model accuracy.
- Saving the Random Forest model using pickle for future use.
