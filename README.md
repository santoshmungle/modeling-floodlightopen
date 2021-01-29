# Modeling Floodlight Open Data to Predict Multiple Sclerosis

## Data

Floodlight Open is an open study by Genentech for healthy controls or patients with multiple sclerosis (MS). The goal is to be able to monitor a patient's progression over time using various tests from a smartphone app. These tests can include mood assessments, hand strength, balance, and general mobility. From a smartphone, Floodlight Open has been able to reference some of the key assessments done by neurologists on MS patients.

## Modeling of ML Classifier

In floodlight open data, there is covariance in the multiple test participated by participant. There were lots of feature engineering performed on the raw floodlight open data before modeling ML classifier to predict multiple sclerosis. 

Logistics Regression and Random Forest was modelled but both perform averagely giving accuracy close to 76% accuracy for both training and testing data. Tuning hyperparameter for Random Forest using Grid Search method improved accuracy significantly for classifier with Random Forest. Tuned Random Forest gave accuracy almost 100% for Training data and 88% for Test data set.
