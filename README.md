# Uber_and_Lyft_Data_Analysis_and_Price_Prediction
In this project, the goal is to develop the inference model to predict the price of Uber and Lyft rides in Boston MA.
The dataset consists of almost 0.7 million examples with missing values.

1. Problem type: supervised (regression)
2. Target variable: price
3. Features are related to distance, date, location, temperature, climate, and sunset.

Machine learning pipeline:
1. Dataset importing, handling of missing values, observing correlation map, and visualizing different attributes.
2. Data preparation using one-hot encoding and split. 
3. Training of the models that include Linear, Polynomial, ElasticNet, and Neural network regression.
4. Evaluation Metric contains a mean square error, root mean square error, and $R^2$(coefficient of determination) score.

Dataset memory usage: 301.4+ MB

## Result

| Metrics        | Linear         | Polynomial  |ElasticNet  |Neural network |
|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|
| MSE|6.367|5.883|5.929|3.679|
| RMSE|2.523|2.425|2.435|1.91|
| R2 score|0.926|0.932|0.931|0.957|

