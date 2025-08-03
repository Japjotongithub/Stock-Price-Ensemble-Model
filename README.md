# Stock-Price-Ensemble-Model

1.The stock price dataset used had 9316 records and 15 columns.The objective of this project is to predict the opening price of next day using previous opening prices and ML model.

2.It includes both market data and economic indicators,along with a target variable. Features include opening price,trading volume,GDP,CPI etc.The target variable is next_day_opening_price.

3.20% of the dataset was used for testing.3 values for the first 3 days in test data are predicted from the start.

4.In Ensemble Model,I used 4 models- Linear Regression,Random FOrest,Gradient Boost and XGBosst. Since Linear regression was performing significantly well,I used weighted average in favour of linear regression.3 predictions are given as output,for next 3 days.

5. RMSE is a key indicator of accuracy, it should be minimal.RMSE of 3.42 means that my model is very accurate.
   
6. I made the graph more interactive by using slicers from Plotly.
