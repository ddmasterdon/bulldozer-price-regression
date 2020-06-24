# Predicting the Sale Price of Bulldozers using Machine Learning

## 1. Problem Definetion

> The goal is to how well we can predict the future sales price of a bulldozer based on its characterstics and previous records of how much similar bulldozers are sold.

## 2. Data

The data is downloaded from Kaggle bluebook for bulldozers competition. 
https://www.kaggle.com/c/bluebook-for-bulldozers/data

There are 3 main datasets:

* Train.csv is the training set, which contains data through the end of 2011.
* Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
* Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

## 3. Evaluation

The evaluation metric is the RMSLE (root mean squared log error) between the actual and predicted auction prices. i.e to minimize RMSLE

## 4. Features

Kaggle provided a data dictionary detailling all the features of the datasheet.