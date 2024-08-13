# Life Expectancy Prediction Project

This repository includes a data analysis project that uses various kinds of predictions to project life expectancy around the world. Enhancing an understanding of the variables that affect life expectancy and developing prediction models to precisely estimate life expectancy are the objectives of this study.

## Table of Contents

- About
- Dataset
- Project Highlights
- Steps Involved
- Features
- Model Evaluation

## About

The project of the research is to determine the various predictor factors and life expectancy relate to one another in diverse nations. Our aim is to develop accurate prediction models that can determine life expectancy by utilizing random forest, decision tree, and linear regression methods. These models are to be developed based on the given features.

## Dataset

The dataset used to estimate life expectancy comprises a wide range of predictor factors and the accompanying life expectancy values for several years across several nations. For the purpose of ensuring data quality and analytic applicability, variables were cleaned and preprocessed.

## Project Highlights

- used the random forest, decision tree, and linear regression algorithms to estimate life expectancy.
- Performed data cleaning and preprocessing to handle missing values and ensure data quality.
- Provided insights into the most influential predictors of life expectancy.

## Steps Involved

1. Data cleaning: Missing values were resolved and categorical variables were converted to factors.
2. Linear Regression:
   _Dropped insignificant variables and outliers.
   _Addressed multicollinearity using VIF analysis.
   _Achieved improved model performance by iterative feature selection.
3. Decision Tree:
   _Utilized the rpart library for building a decision tree model.
   _Employed 5-fold cross-validation for model evaluation.
4. Model Evaluation:
   _Calculated metrics such as RMSE, MAPE, and MAE for each model.

## Features

- Data exploration and preprocessing.
- Linear regression analysis with iterative refinement.
- Decision tree modeling with visualization.
- Model evaluation using key metrics.

## Model Evaluation

The life expectancy prediction models are evaluated using key metrics such as RMSE (Root Mean Squared Error), MAPE (Mean Absolute Percentage Error), and MAE (Mean Absolute Error). These metrics provide insights into the accuracy and performance of the models in estimating life expectancy.
