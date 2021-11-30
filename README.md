# FlightDelayPrediction
This repository contains the code for a two-staged pipelined ML Engine consisting of a classifier and a regressor to model the on-time performance of flights using SciKit-Learn. 

The flight dataset contained flight data for aiports in the US, including the arrival and departure delay, for they year 2017. The weather dataset contained the weather information at the airports for over the year. 
The preprocessing notebook contains code for merging of the datasets.

For both the classifier and the regressor, the performance of Logistic and Linear Regressor, Decision Trees, Extra Trees, Random Forest and Gradient Boosting were compared.

SMOTE Oversampling was done on the dataset to reduce data imbalance. Regression Analysis was performed to evalute the performance of the regressor in different ranges. 


