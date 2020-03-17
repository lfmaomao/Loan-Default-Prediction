# Loan Default Prediction


## Motivation

Lending Club is a peer-to-peer lending platform that utilizes a group of private investors to fund loan requests. 

The business problem of this project is that investors require a more comprehensive assessment of these borrowers in order to reduce the risk of their investment. 

## Dataset

The data set is from Lending Club, which can be downloaded [here](https://www.lendingclub.com/info/statistics.action).

The dataset contains 421097 loan records, and 145 features. 

## Installation

The build-in libraries from Anaconda needed to run this project include:

- pandas
- numpy
- matplotlib
- seaborn
- pylab
- time
- xgboost
- lightgbm
- sklearn

## Results

In this project, I utilized the historic loan dataset from Lending Club, which contains over 200,000 loan records with a hundred features. I built xgboost and lightgbm models, such a model will help investors identify the borrowers who are likely to default. The tuned model resluts in an AUC of 0.72 on test dataset.