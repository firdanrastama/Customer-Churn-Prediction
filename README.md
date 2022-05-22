# Project: Predicting Customer Churn

## Introduction

This repository contains an end-to-end data analysis and build a machine learning model to predict customer churn. The goal of this project is to build a model which can predict whether or not a customer will stop using the services of the business which can lead to significant losses.

Link for the jupyter notebook [Customer Churn Project](https://github.com/firdanrastama/Customer-Churn-Prediction/blob/main/customer_churn_prediction.ipynb).

## Problem Statement

Churn is when a customer stops doing business or ends a relationship with a company. It’s a common problem across a variety of industries and a company that can predict churn can take proactive action to retain valuable customers and get ahead of the competition. Predicting customer churn is critical for companies. It is more costly to acquire new customers than to retain existing ones.

## Evaluation metric

The evaluation metric of this project is the recall score, since in the dataset we have a imbalanced classes accuracy is not a good metric for this case and we will have a recall score of the metric in this project

## Steps of the project
- Import libraries
- Import and reading data 
- Exploratory Data Analysis
- Data Preprocessing
- Data modeling and model evaluation
- Comparing the models
- Feature Engineering

## Summary

We started by cleaning the data and analyzing it with visualization. Then, to be able to build a machine learning model, we transformed the categorical data into numeric variables. After transforming the data, we tried 4 different machine learning algorithms using default parameters and tuned the hyperparameters with GridSearchCV. And we found our best model **XGBoost** obtaining recall of **85%** and auc score of 93%
