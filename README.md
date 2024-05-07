# Birth_weight_intervals_prediction
This is a repository with notebooks from Kaggle Competition https://www.kaggle.com/competitions/prediction-interval-competition-i-birth-weight
The task was to create a regression model having the narrowest (most "efficient") overall prediction intervals.
Overall performance of proposed model accesed by the mean of the Winkler Interval score. A valid submission must have had a nominal marginal coverage of 90% (i.e. α=0.1).
Baseline model used XGBoost for prediction and QuantileRegression for metric calculation.

