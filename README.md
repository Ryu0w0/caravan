# Caravan

It is performed by R.

## Introduction
It is a binary classification task that predicts whether a customer likely to purchase the caravan policy or not. It was originally a KDD data challenge and its detail is provided at [TIC](http://kdd.ics.uci.edu/databases/tic/). Data used in this project comes from [here](http://kdd.ics.uci.edu/databases/tic/tic.html).

This project addressed 2 problems below;

1. Predicting who are likely to be interested in purchasing a caravan insurance policy.
2. Explaining why such a prediction was made.

Actual implementation is written in R and placed at `./notebook/caravan.jpynb`

## Outline
This project perform several tasks below;

1. Data exploration
   - Overview of data
     - Data types, representative values
   - Variable interpretation
   - Nature of variables
     - Distribution with histogram
   - Relationships among variables
     - Correlation coefficient with heatmap
     - Correlation ratio with histogram
   
2. Model selection

   - Justification of the selection
   - Logistic Regression (L1/L2) and Linear Discriminant Analysis

3. Pre-processing

   - Removing unnecessary variables
   - Dummy variable generation

4. Feature selection

   - Forward stepwise selection
   - Best subset selection based on AIC, BIC and Cp

5. Modelling

   - Cross-validation and hyper-parameter tuning

   - Measure the performance of models
   - Model comparison

6. Analysis

   - Important features for the prediction
