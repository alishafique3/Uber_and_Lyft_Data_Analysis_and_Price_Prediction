# Uber and Lyft Data Analysis and Price Prediction
## Problem Statement
In this project, the goal is to develop a regression model to predict the price of Uber and Lyft rides in Boston MA.
The dataset consists of almost 0.7 million examples with missing values with the following details:

1. Features are related to distance, date, location, temperature, climate, and sunset.
2. Target variable: price (continuous numerical dtype)
3. Problem type: supervised (regression)

## Machine learning pipeline:
1. Import the dataset, handle the missing values, observe the correlation map, and visualize the different attributes.
2. Prepare the dataset using one-hot encoding and split the dataset. 
3. Train the models that include Linear, Polynomial, ElasticNet, and Neural network regression.
4. Evaluation Metric contains a mean square error (MSE), root mean square error (RMSE), and $R^2$(coefficient of determination) score.

Dataset memory usage: 301.4+ MB

## Result

| Metrics        | Linear         | Polynomial  |ElasticNet  |Neural network |
|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|
| MSE|6.367|5.883|5.929|3.679|
| RMSE|2.523|2.425|2.435|1.91|
| R2 score|0.926|0.932|0.931|0.957|

## References
1. Base NN Code: Uber and Lyft Dataset NN - vaibhav007 - [Link](https://www.kaggle.com/code/vaibhavkumbhar/uber-and-lyft-dataset-nn)
2. Dataset: BM, Uber, and Lyft Dataset Boston, MA [Link](https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma)
