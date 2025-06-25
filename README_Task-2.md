📈 NVIDIA Stock Price Prediction with Linear Regression
This repository contains a Jupyter Notebook that demonstrates a simple machine learning pipeline to predict the next day's closing price of NVIDIA (NVDA) stock using historical stock data and Linear Regression.

🚀 Project Overview
The notebook includes the following steps:

✅ Data Collection: Historical NVDA stock data downloaded using the yfinance library (last 2 years)

✅ Data Preparation:

Features: Open, High, Low, Volume

Target: Next Close Price (next day's closing price)

Data cleaning and handling of missing values

✅ Model Training:

Using LinearRegression from scikit-learn

Train-test split for evaluation

✅ Model Evaluation:

Performance measured using Mean Squared Error (MSE)

Visualization: Actual vs Predicted Closing Prices

🔧 Tools & Libraries Used
yfinance: For downloading stock data

pandas: For data manipulation

matplotlib: For data visualization

scikit-learn: For machine learning (regression, evaluation)

📊 Sample Output
📉 Actual vs Predicted Closing Prices plotted for test data

📉 Mean Squared Error reported for prediction accuracy

plaintext
Copy
Edit
Mean Squared Error: 8.42
💡 Future Improvements
Incorporate more features like technical indicators (e.g., moving averages, RSI)

Try more advanced models (e.g., XGBoost, LSTM)

Perform hyperparameter tuning and cross-validation
