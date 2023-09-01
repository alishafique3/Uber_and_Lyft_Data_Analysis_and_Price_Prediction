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
Colons can be used to align columns.

| Regression Model        | MSE           | RMSE  |$R^2$ score  |
| :-------------: |:-------------:|:-----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
