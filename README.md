# ML-Retail-Demand-Forecasting-Model

This demand forecasting model uses Random Forest regression to predict the units sold of a retail chain (on a weekly basis) given the retail chain's past sales data. RandomizedSearchCV is used to tune the hyperparameters of this model.

Sales data input:
record_ID
week
store_ID
sku_ID
total_price
base_price
is_featured_sku
is_display_sku

Output:
Mean Absolute Error
week-by-week comparison of predicted values versus actual values

Features included in training model:
discount 
discount percentage
lagged features (sales over past 4 weeks)
moving average of units sold

The dataset that this model was trained on is found at https://www.kaggle.com/datasets/aswathrao/demand-forecasting?resource=download&select=train_0irEZ2H.csv
