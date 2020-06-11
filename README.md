# Genpact Machine Learning Hackathone:Food-Demand-Forecasting
## The model based on Decision Tree algorithm predicts the number of food orders for various cities for a meal delivery company.
Decision Tree Model trained on train.csv 
The evaluation metric used is 100*RMSLE where RMSLE is Root of Mean Squared Logarithmic Error
across all entries in the test set.
Feature selection using Pearson correlation matrix.
Hyperparametric tuning isnt done.
## The code can be run on jupyter notebook through anaconda prompt. The model learned then make predictions on entries in test.csv and automatically publishes a csv file containing id (test id) and relative prediction.
