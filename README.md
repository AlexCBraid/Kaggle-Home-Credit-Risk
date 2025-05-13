# Kaggle Home Credit Default Risk Competition Solution

This repository contains my solution for the Kaggle Home Credit Default Risk competition. The goal of this competition was to predict the probability of loan default for credit applicants.

## Project Description

In this project, I developed a machine learning model to assess credit risk. I worked with a variety of data sources, including:

* Application data
* Bureau data
* Previous application data
* POS cash balance data
* Credit card balance data
* Installments payments data

The solution involves the following key steps:

1.  **Data Preprocessing**: Cleaning, transforming, and merging the various data sources.
2.  **Feature Engineering**: Creating new features to improve model performance.  Key features included credit-to-annuity ratio and aggregated information from other data sources.  I also experimented with network features.
3.  **Model Development**: Training a LightGBM model to predict loan default.  I experimented with a two-stage modeling approach and ensembling.
4.  **Model Validation**: Using cross-validation to evaluate model performance and mitigate overfitting.

## Key Findings

* Effective feature engineering is crucial for this type of problem.
* Ensembling different models can improve overall performance.
* Careful attention to cross-validation is necessary to avoid overfitting.

## Technical Approach

* Programming Language: Python
* Libraries: Pandas, NumPy, Scikit-learn, LightGBM
* Modeling Approach
    * Feature Engineering
    * LightGBM
    * Ensembling

## Results

My best solution was an ensemble of two models.

## Future Work

* Further hyperparameter tuning.
* Explore additional feature engineering techniques.
* Experiment with other machine learning models.
