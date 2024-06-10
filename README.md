# SF-Real-Estate-Forecast-System

This repository contains code and analysis for building and evaluating machine learning models aimed at predicting median house values. We use various regression techniques, including Random Forest and Gradient Boosting, to model house prices based on features such as median income, total rooms, and geographical coordinates.

## Overview

The project seeks to determine how well different features can predict the value of houses. The repository includes several plots to visualize the performance and diagnostics of the models, learning curves to understand model learning behavior, and feature importance graphs to highlight which features most influence predictions.


## Models

### Random Forest Regressor
- Utilizes ensemble learning to predict housing values based on non-linear and complex relationships between variables.
- `RandomForestRegressor` from scikit-learn is configured with optimized parameters for best performance.

### Gradient Boosting Regressor
- Employs boosting techniques to make predictions, which is effective in reducing bias and variance.
- `GradientBoostingRegressor` from scikit-learn helps in handling various types of data imperfections such as outliers, missing labels, and high dimensionality.

## Key Visualizations

- **Residual Plots**: To check for any obvious patterns that might indicate issues with model assumptions.
- **Prediction Error Plots**: To visually assess how well the predictions are compared to the actual values.
- **Learning Curves**: To determine if the model benefits from more training data or if it suffers from high variance or bias.
- **Feature Importance**: To understand which features most affect the predictions in Random Forest and Gradient Boosting models.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your suggested changes.
