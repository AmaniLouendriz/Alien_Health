# AI_assignements
This repo is my assignments for the introduction to AI course. 

# Assignement 1

I was provided with a synthetic dataset: https://raw.githubusercontent.com/turcotte/csi4106-f25/main/assignments-data/a1/alien_pet_health.csv 

It contains some attributes related to the health indicators of aliens. The assignement 1 evolves around cleaning data and preparing the data to be analyzed in assignement2 where a model
is trained to detect whether a certain individual is healthy or not depending on certain indicators. You can execute the notebook in google collab. The alien_pet_health_cleaned.csv 
is the result of the data cleaning and the statistical analysis of the first assignement.

# Assignement 2

In this assignement, I trained different ml models like the k-neighbors classifier, logistic regression, decision trees and random forests, after having encoded and normalized data to minimize bias. The performance of the models was quantified using cross validation, and different hyperparameters were evaluated before choosing the hyperparameter combination that maximized performance.

The performance of the model was also evaluated against a new dataset that contained missing data, the dataset was imputed by either using the median of numerical attributes or the highest frequency of the categorical attributes before feeding it to the ml model.
