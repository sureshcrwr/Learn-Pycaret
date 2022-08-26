# Learn-Pycaret

PyCaret for Machine Learning
It is a bundle of many Machine Learning algorithms.
Only three lines of code is required to compare 20 ML models.
Pycaret is available for:
Classification
Regression
Clustering
1. Self Learning Resource
Tutorial on Pycaret for Regression, Classification and Clustering Click Here

2. In this tutorial we will learn
Getting Data: How to import data from PyCaret repository
Setting up Environment: How to setup an experiment in PyCaret and get started with building regression/classfication/clustering models
Create Model: How to create a model, perform cross validation and evaluate regression metrics
Tune Model: How to automatically tune the hyperparameters of a regression model
Plot Model: How to analyze model performance using various plots
Finalize Model: How to finalize the best model at the end of the experiment
Predict Model: How to make prediction on new / unseen data
Save / Load Model: How to save / load a model for future use
3. Three line of code for model comparison for "Insurance" dataset
from pycaret.datasets import get_data
from pycaret.regression import *

insuranceDataSet = get_data("insurance")
s = setup(data = insuranceDataSet, target='charges', silent=True)
cm = compare_models()
4. Outcome for Regression
image

5. Outcome for Classification
image

6. Outcome for Clustering
image
