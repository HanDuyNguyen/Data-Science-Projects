# Predicting the Stock Movement using Machine Learning

In this notebook, we are going to go through a machine learning project with the goal of predicting the stock movement of an unknown asset.

## Problem definition

> How well can we  predict stock movement based on real-market orderbook data ?

## Data

The full dataset data-training.csv can be downloaded from https://challenge.xtxmarkets.com/ under the Data Download section.

## Evaluation

The evaluation metric for this competition is the r2 score. For more information about the r2 score check: https://en.wikipedia.org/wiki/Coefficient_of_determination.

For more on the evaluation of this project check: https://github.com/correlation-one/XTXStarterKit/tree/dev/src.

## Features

The data features can be grouped into four groups: askRate, askSize, bitRate, bitSize. Each group has 14 features, for example askRate1,...,askRate14. 

## Instruction

* <code>XTX_EDA.ipynb</code> contains the codes for Exploratory Data Analysis.
  
* <code>XTX_LSTM.ipynb</code> contains the Long-Short-Term memory model.
  
* <code>XTX_XGBoost.ipynb</code> contains the XGBoost model which give the lowest test error.  

