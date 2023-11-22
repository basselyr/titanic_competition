# Titanic Survivors Competition Attempt
## By Bassel Rezk -- Kaggle.com

This repo includes a notebook of my approach to solve the classification problem of "Titanic - Machine Learning from Disaster" which can be found here: https://www.kaggle.com/competitions/titanic/overview
In this notebook, I have applied data preprocessing using exploratory data analysis, a wide variety of imputing strategies for missing values and feature scaling.
Afterwards, I trained a feed-forward neural network (tuned using Bayesian Optimization), a Gaussian Naive-Bayes model, an XGBoost model, a CatBoost model (tuned using Randomized Search), a Random Forest model, an SVM model (tuned using Grid Search) and a K-Nearest Neighbors model.
All of the abovementioned models were tested for accuracy using 10-Fold Cross Validation, which showed that the neural network provided the best accuracy.
Accordingly, the neural network model of the top 5 tuned hyperparameters which returned the best accuracy in cross validation was used to predict the test set, yielding a 76.8% accuracy.