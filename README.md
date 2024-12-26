# Variable Importance and Performance in Food Delivery (Delhi)

## Project Description

This project aims to determine factors that influence food delivery time in Delhi, India, using the XGBoost algorithm. The model is trained with a dataset from Kaggle containing information about food orders, such as order value, delivery fee, commissions, payment processing costs, refunds, discounts, and delivery time.

## Problem

The original project focused on a hospital context, but this project expands the analysis to the food delivery scenario in Delhi. The goal is to understand the factors that influence delivery time and build a model that helps generate insights to improve delivery time performance with greater accuracy.

## Approach

The project utilizes the XGBoost algorithm to build a predictive model. The data is pre-processed and divided into training and testing sets. The model is evaluated based on metrics such as R² and RMSE.

## Results

The XGBoost model showed promising performance in predicting delivery time, with an R² of 0.45 in validation. The most important features for the model were delivery hour, order value, and commission fee.

## Limitations

The project has some limitations, such as the lack of data on traffic and weather conditions, which can influence delivery time. In addition, the model was trained with a specific dataset from Delhi and may not be generalizable to other cities.

## How to use

1. Clone the repository: `git clone <repository_url>`
2. Install the dependencies: `pip install -r requirements.txt`
3. Run the notebook: `jupyter notebook`

## Contact

- Name: Davi
- Email: davirjr@gmail.com
- LinkedIn: [https://www.linkedin.com/in/davi-rodrigues-junior-b1b822b4/](https://www.linkedin.com/in/davi-rodrigues-junior-b1b822b4/)
