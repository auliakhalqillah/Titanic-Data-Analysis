# Titanic Data Analysis

## Overview

The objective, in this case, is to create a model prediction of the survival of the passengers from RMS Titanic. The dataset is downloaded from Kaggel. There are three datasets, training file, testing file, and gender submission file. The training data file will be used to train our model prediction. The testing file will be used to test our model prediction. The gender submission file is a prediction file given by Kaggle. I use this submission file to check our accurate model. Let's get started.

The traing datasets have 891 rows data and 12 columns. The 12 columns are

- PassengerId : the unique id of passenger
- Survived : the survival information of passenger (0 = No, 1 = Yes)
- Pclass : the passenger's class on RMS Titanic
- Name : the passenger's name
- Sex : the passenger's sex (male or female)
- Age : the passenger's age
- SibSp : the number of siblings or spouses aboard the Titanic
- Parch : the number of parrents or childrens aboard the Titanic
- Ticket : the passenger's ticket number
- Fare : the passenger's fare
- Cabin : the passenger's cabin number
- Embarked : the port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

In this excercise, I create a model prediction by using Logistic Regression

## Source

Kaggle: https://www.kaggle.com/c/titanic/data
