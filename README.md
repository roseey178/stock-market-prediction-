Collected historical S&P 500 data using the yFinance API and processed the dataset by removing dividends and stock splits.
Created a target variable to predict if the stock’s Closing Price will be higher the following day.
Trained a Random Forest Classifier with key predictors: Close, Volume, Open, High, and Low prices.
Implemented a backtesting framework to evaluate model performance on historical data, predicting future stock movements in predefined steps.
Incorporated rolling averages and trend features for multiple time horizons (2, 5, 60, 250, 1000 days) to capture short- and long-term market trends.
Refined the prediction threshold to improve precision by adjusting probability cut-offs.
Assessed model accuracy using precision scores and other evaluation metrics, ensuring reliable stock movement predictions.
