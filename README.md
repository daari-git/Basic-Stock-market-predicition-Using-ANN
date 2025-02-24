# Basic-Stock-market-predicition-Using-ANN
# Stock Price Prediction using a Simple Neural Network

This project implements a basic neural network for predicting stock prices using historical data. It uses a single hidden layer with sigmoid activation and updates weights using forward and backward propagation.

## Dataset

The dataset used is `Tesla_Stock_Cleaned (1).csv`, which contains historical Tesla stock prices. The script performs preprocessing, including handling missing values and normalizing the target variable.

## How It Works

1. **Data Preprocessing:**

   - Converts relevant columns to numeric values
   - Handles missing data using mean imputation
   - Normalizes the target variable

2. **Neural Network Implementation:**

   - Initializes random weights and biases
   - Uses a single hidden layer with sigmoid activation
   - Implements forward propagation
   - Computes error and performs backpropagation to update weights

3. **Prediction and Evaluation:**

   - Predicts the next day's stock price
   - Denormalizes the predicted value
   - Calculates error metrics (MAE, MSE, MAPE, R1 Score)

## Output

The script prints the following:

- Predicted next-day price
- Actual next-day price
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Mean Absolute Percentage Error (MAPE)
- Custom R1 Score
- Prediction Accuracy

## Example Output

```
Predicted Next Day Price: 675.32
Actual Next Day Price: 680.45
Mean Absolute Error (MAE): 5.13
Mean Squared Error (MSE): 26.32
Mean Absolute Percentage Error (MAPE): 0.75%
Custom R1 Score: 0.9924
Prediction Accuracy: 99.25%
```

## Improvements

- Add more hidden layers for better prediction accuracy
- Experiment with different activation functions
- Use more advanced models like LSTMs for sequential data

## Author

[Subash Khanal]
