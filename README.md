# Comprehensive Machine Learning Regression Pipeline
An end-to-end Python project demonstrating a complete workflow for data preprocessing, feature engineering, advanced feature selection, and performance comparison of multiple regression models.

# Project Overview
This repository provides a systematic approach to building and evaluating regression models. The primary goal is to explore how different feature selection techniques impact the performance of various models, including K-Nearest Neighbors, Ridge, Support Vector Machines (with RBF and Polynomial kernels), Random Forest, and a Multi-layer Perceptron, with tuning their hyperparameters by GridSearchCV.

# Workflow & Features
The project follows a structured machine learning pipeline:
- Data Cleaning: Robust methods for handling missing or null values.
- Feature Engineering: Techniques to create new, meaningful features from the existing data to improve model performance.
- Outlier Analysis: Implementation of algorithms to detect and handle outliers that could skew the model's accuracy.
- Feature Selection: Multiple strategies for selecting the most relevant features, including: Filter methods like Chi-Squared, correlation coefficients, Information Gain, Wrapper methods like RFE, forward/backward feature selection, Embedded methods like LASSO, and ...
- Exploratory Data Analysis (EDA): Generation of plots to understand feature distributions, correlations, and variations. Includes histograms, scatter plots, and heatmaps.
- Model Training: Training and evaluation of several popular regression models on different feature subsets.
Comparative Analysis: A clear comparison of model performance metric (RMSE) to determine the best-performing model and feature set.

# Models Implemented
The following machine learning models are trained and evaluated in this project:

K-Neighbors Regressor (KNN)
Ridge Regression
Support Vector Regressor (SVR) with RBF Kernel
Support Vector Regressor (SVR) with Polynomial Kernel
Random Forest Regressor
Multi-Layer Perceptron (MLP) Regressor

# Dataset
This project utilizes the Ames Housing Dataset from Kaggle. It contains 2930 rows and 258 columns, with the primary objective of predicting the Sale Price variable.
