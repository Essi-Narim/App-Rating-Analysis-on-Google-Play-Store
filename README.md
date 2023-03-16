# App Rating Analysis on Google Play Store

## Project Overview

This project investigates the relationship between the rating of an app on Google Play and its different characteristics such as category, price, and number of reviews. The data used in this project was collected from a Google dataset featuring 10,000 Google Play Store apps and can be found [here](https://www.kaggle.com/datasets/lava18/google-play-store-apps).

The following five Data Science steps were taken to analyze the data set:

1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Modeling via Machine Learning algorithms

## Conclusions

The results of the analysis showed that there was no substantial relationship observed between the rating of an app and its category, price, and number of reviews. Three machine learning algorithms (Random Forest Regressor, MLPRegressor, and Linear Regression) along with two different conversion techniques for categorical variables into numerical variables (hot-one encoding and label encoding) were applied. The results showed that Random Forest Regressor with one-hot encoding resulted in a better comparative accuracy (R-squared score), however, no meaningful correlation between the mentioned variables was detected.

## Repository Structure

The repository contains the following files:

- Jupyter Notebook containing the code and analysis
- README.md file (this file)
- The data set used in csv format.

## Requirements

To run the code in the Jupyter Notebook, you will need to have the following libraries installed:

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Sklearn

## How to use the repository

1. Clone the repository to your local machine
2. Open the Jupyter Notebook file
3. Run the code in the notebook

Note: Make sure to have all the required libraries installed before running the code.
