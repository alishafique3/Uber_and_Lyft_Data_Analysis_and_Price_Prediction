# Uber_and_Lyft_Data_Analysis_and_Price_Prediction
In this project, the goal is to develop the inference model to predict the price of Uber and Lyft rides in the Boston MA.
The dataset consists of almost 0.7 million examples with missing values.

1. Problem type: supervised (regression)
2. Target variable: price
3. Features are related to distance, date, location, temperature, climate and sunset.

Machine learning pipeline:
1. Dataset importing, handling of missing values, observe correlation map and visualize different attributes.
2. Data preparation using one hot encodding and split. 
3. Training of the models that include Linear, Polynomial, ElasticNet and Neural network regression.
4. Evaluation Metric contains mean square error, root mean square error and $R^2$(coefficient of determination) score.
