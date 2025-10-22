# Predicting-Road-Accident-Risk
My solution for Kaggle’s Playground Series S5E10 — Predicting Road Accident Risk. This project explores feature engineering, model optimization, and evaluation techniques to predict the likelihood of road accidents using real-world-style data.

This project focuses on building a predictive model that estimates the probability of a road accident given structured data inputs.
It demonstrates end-to-end data science workflow — from data cleaning and feature engineering to model training, evaluation, and submission generation.

Competition link:
https://www.kaggle.com/competitions/playground-series-s5e10

Approach

Data Exploration:
Analyzed variable distributions, correlations, and outliers.

Feature Engineering:

Extracted time-based features (hour, weekday, month).

Encoded categorical variables (weather, road type, region).

Added interaction features and statistical aggregates.

Modeling:

Trained ensemble models such as LightGBM, CatBoost, and XGBoost.

Performed hyperparameter tuning with Optuna.

Combined models using weighted averaging.

Evaluation:

Used Stratified K-Fold cross-validation to ensure balanced splits.

Tracked AUC / F1-score (depending on Kaggle’s metric).
