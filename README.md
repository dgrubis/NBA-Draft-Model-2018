# NBA-Draft-Model-2018
Jupyter notebook that outlines the process of creating a machine learning predictive model. Predicts the peak "Wins Shared" by the current draft prospects based on numerous features such as college stats, projected draft pick, physical profile and age. I try out multiple models and pick the best performing one for the data from my judgement. 

Uses linear regression, a neural network multi-layer perceptron regressor, ridge regression, lasso regression and a linear support vector regression.

All models were created with scikit-learn. 

Database was built from scratch from RealGm, Basketball Reference and NBA.com.

*Since database was built from scratch I don't have as much data points as I'd like so model results experience pretty significant variance.

*Wins shared also is a metric that has flaws so not a perfect measure for predicting NBA success. 

"draft_model_cleaning" is a python file where I merged and exported csv files to create the database.
