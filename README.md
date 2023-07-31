# stock_price_prediction_Asterisc_Task3

## Objective

The objective of this project is to build a predictive model that can forecast stock prices based on historical data. The model utilizes machine learning techniques to analyze market trends, technical indicators, and other relevant features to make predictions about future stock prices.

## Dataset

The historical stock price data used in this project can be found in the `historical_stock_data.csv` file. The dataset contains the following columns:
- `Date`: The date of the stock price data.
- `Open`: The opening price of the stock on that date.
- `High`: The highest price reached by the stock on that date.
- `Low`: The lowest price reached by the stock on that date.
- `Close`: The closing price of the stock on that date.
- `Adj Close`: The adjusted closing price of the stock on that date.
- `Volume`: The trading volume of the stock on that date.

## Steps Involved

The project involved the following steps:

1. Data Collection: Gathering historical stock market data for analysis.

2. Data Preprocessing: Cleaning and preparing the data for analysis.

3. Feature Engineering: Creating relevant features and indicators for predicting stock prices.

4. Model Selection: Choosing the appropriate machine learning algorithm for regression tasks.

5. Model Training: Training the selected model on the training data.

6. Hyperparameter Tuning: Fine-tuning the model to optimize its performance.

7. Model Evaluation: Evaluating the model's performance on the testing dataset.

8. Visualization and Interpretation: Visualizing the predictions and model performance.

## Model Details

The model used in this project is a Gradient Boosting Regressor. Gradient Boosting is an ensemble learning technique that combines multiple weak learners (decision trees) to create a more robust predictive model.

## Usage

To run the stock price prediction model, follow these steps:

1. Clone the repository to your local machine.

2. Ensure you have Python and the required libraries installed.

3. Run the `stock_price_prediction.py` script to train and test the model.

## Dependencies

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib

## Results

The performance of the predictive model was evaluated using mean squared error (MSE) and mean absolute error (MAE). The model achieved reasonable accuracy in predicting stock prices, but keep in mind that the stock market is highly unpredictable, and no model can guarantee perfect predictions.
