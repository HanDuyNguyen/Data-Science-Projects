# Predicting true or fake Tweets using Machine Learning

In this notebook, we are going to use machine learning to predict which Tweets are about real disasters and which ones are not.

## 1. Problem definition

>  How well can we predict whether a tweet is real or not given the tweet itself ?

## 2. Data 

The data is downloaded from the Kaggle NLP Getting Started for the Real or Not? NLP with Disaster Tweets competition: 
https://www.kaggle.com/c/nlp-getting-started/data

There are 3  main datasets:

* Train.csv - the training set
* Test.csv - the test set
* Sample_submission.csv - a sample submission file in the correct format

## 3. Evaluation

The evaluation metric for this project is the F1 between the predicted and expected answers.

For more on the evaluation of this project check: https://www.kaggle.com/c/nlp-getting-started/overview/evaluation.

## 4. Features

There are 3 main features:

* text - the text of the tweet
* location - the location the tweet was sent from (may be blank)
* keyword - a particular keyword from the tweet (may be blank)
# Instructions

* <code> Embedding_and_LSTM.ipynb </code> contains the Long-Short-Term model which give the highest accuracy.
* <code> BernoulliNB.ipynb </code> contains the Bernoulli Naive Bayes model.
