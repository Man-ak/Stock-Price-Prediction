# Linear Regression Model for Stock Price Prediction

This Python script demonstrates how to use a simple linear regression model to predict stock prices based on historical data. The script utilizes the scikit-learn library for linear regression and pandas for data manipulation.

## Prerequisites

Before running the script, make sure you have the following dependencies installed:

- NumPy
- Matplotlib
- Pandas
- scikit-learn (sklearn)

## Code Overview

- The script reads the CSV data and extracts the 'High', 'Low', 'Open', and 'Volume' features as input (X) and the 'Close' 
  price as the target (y).
- It splits the data into training and testing sets using the train_test_split function from scikit-learn.
- A Linear Regression model is created and trained using the training data.
- The model is used to make predictions on the testing data.
- Performance metrics, such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE), are 
  calculated and displayed.
- The top 20 actual and predicted stock prices are visualized using a bar chart.

## Accuracy Table

Here is an accuracy table for the model's performance:
| Metric                      | Value               |
|-----------------------------|---------------------|
| Mean Absolute Error (MAE)   | 46%                 |
| Mean Squared Error (MSE)    | 90%                 |
| Root Mean Squared Error (RMSE) | 95%              |

