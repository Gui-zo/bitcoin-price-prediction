# bitcoin-price-prediction
This project has the intention to apply a machine learning model to predict the price of bitcoin using different indicators as features.

Keep in mind this is supposed to be a very simple model, without open and close prices, based solely on the indicators to figure out if the day is going to be positive or not. I will soon add to the complexity of the model with a variety of different features in order to compare to this one. This model is **NOT** financial advice, use at your own risk.


| Feature | Explanation |
| --- | ----------- |
| MA 7 | Moving Average of the last 7 days |
| MA 20 | Moving Average of the last 20 days |
| MA 50 | Moving Average of the last 50 days |
| RSI 7 | Relative Strenght Index of the last 7 days |
| RSI 14 | Relative Strenght Index of the last 14 days |
| RSI 21 | Relative Strenght Index of the last 21 days |
| Weekday | Day of the week (0 - Sunday, 1 - Monday, 2 - Tuesday, 3 - Wednesday, 4 - Thursday, 5 - Friday, 6 - Sunday)
| Is_month_start | 1 if the day is between the 1st and 7th day of the month.
| Is_month_end | 1 if the day is between the 24th and last day of the month.