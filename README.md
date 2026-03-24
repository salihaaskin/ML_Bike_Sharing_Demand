# Bike Sharing Demand Prediction
This project focuses on predicting bike rental demand using machine learning techniques.
By analyzing historical data such as weather conditions, time, and seasonal trends, the goal is to build a model that accurately forecasts the number of bike rentals.

## Project Structure
├── ML&AL Bike Sharing Demand.ipynb   # Main notebook with analysis and models

├── data/                             # Dataset

├── README.md                         # Project documentation


## Dataset
The dataset contains information about bike rentals along with features such as:

Date and time

Temperature

Humidity

Wind speed

Season and weather conditions

Number of rentals (target variable)

## Workflow

Data Loading

Import dataset and inspect structure

Data Formatting

Visualize trends and patterns

Identify relationships between features and demand

Feature Engineering

Extract time-based features (hour, day, month)

Encode categorical variables

Model Building

Train machine learning models such as:

Linear Regression

Decision Trees / Random Forest

Evaluation

Metrics like RMSE / MAE

Compare model performance

## Models Used
Linear Regression

Lasso and Ridge Regularizations

KNN Regression

Decision Tree / Random Forest

Gradient Boosting

## Results
The model performance is evaluated based on prediction accuracy.
Key insights include:

Time of day strongly influences demand

Weather conditions significantly affect rentals

Seasonal patterns are important predictors

### Common libraries used:

Python 3.x
pandas
numpy
matplotlib / seaborn
scikit-learn
