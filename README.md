# Boston-Read-Estates-Data-Analysis-Project

**Compnay** : CODETECH IT SOLUTIONS

**NAME** : DEEPAK KASHYAP

**INTERN ID** : CT4MIET

**DOMAIN** : DATA ANALYST

**BATCH DURATION** : January 10th, 2025 to May 10th, 2025

**MENTOR NAME** : NEELA SANTOSH

** Project Overview
This project focuses on building a machine learning model to predict housing prices in Boston using the Boston Housing dataset. The dataset contains various features that influence house prices such as crime rate, number of rooms, and accessibility to highways, which are used to develop a reliable model for real estate valuation. The aim of this project is to explore the data thoroughly, visualize the correlations, build a pipeline for preprocessing, and then apply a regression model that can effectively estimate house prices. This end-to-end pipeline follows the standard data science workflow—from data loading, cleaning, and transformation to model training, testing, and evaluation. This project is especially helpful for real estate companies like “Dragon Real Estates” that want to make informed pricing decisions based on data-driven insights.

Dataset Summary
The Boston Housing dataset contains 506 instances with 13 numerical features and one target variable (PRICE). Some of the prominent features include:
•	CRIM: Crime rate per capita
•	RM: Average number of rooms per dwelling
•	LSTAT: % lower status population
•	PTRATIO: Pupil-teacher ratio
•	DIS: Weighted distance to employment centers
The target variable, PRICE, represents the median value of owner-occupied homes in $1000s.
Tools & Technologies Used
•	Python (Pandas, Numpy, Seaborn, Matplotlib, Sci-kit Learn).
Exploratory Data Analysis (EDA)
•	Visualized histograms of features to check for skewness and outliers.
•	Identified strong correlations using a heatmap (e.g., RM and LSTAT had high correlation with PRICE).
•	Detected missing values and ensured data completeness before modelling.

Data Preprocessing
•	Split the data using Stratified ShuffleSplit based on income categories to maintain distribution.
•	Used SimpleImputer to fill in missing values (median strategy).
•	Implemented StandardScaler to normalize data.
•	Designed a pipeline using ColumnTransformer to streamline preprocessing tasks.

Model Building
•	Chose Linear Regression for baseline model training.
•	Used cross-validation with scoring metric negative mean squared error to evaluate performance.
•	Calculated Root Mean Squared Error (RMSE) on both validation and test sets.

Final Model Evaluation:
After training and evaluating the model using stratified testing and cross-validation:
•	Final RMSE (Test Set): 4.93 
•	Average Cross-Validated RMSE: 5.04 with standard deviation 0.41
Sample Prediction
The model returned a predicted price close to $22.33, which aligns well with the expected pricing in the Boston housing market.**
