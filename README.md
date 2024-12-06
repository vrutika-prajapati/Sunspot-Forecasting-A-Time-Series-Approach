# Sunspot-Forecasting-A-Time-Series-Approach

This repository contains a project that uses the Prophet library to predict sunspot activity based on historical monthly data. The goal is to forecast future sunspot numbers using different growth models and evaluate the accuracy of the predictions using various performance metrics.

## Project Overview

The Sunspot Prediction project is aimed at using time series forecasting to predict sunspot numbers. The main steps include:

1. **Data Preprocessing**: Cleaning and transforming historical sunspot data for modeling.
2. **Modeling with Prophet**: Using Prophet to build models for linear, flat, and logistic growth.
3. **Prediction & Evaluation**: Forecasting future sunspot numbers and evaluating the model performance using metrics like Mean Absolute Error (MAE) and R-squared (R²).
4. **Visualization**: Visualizing the historical data and the predicted sunspot numbers.

### Models Used:
- **Linear Growth**: Assumes linear progression over time.
- **Flat Growth**: Assumes no growth and is used as a baseline.
- **Logistic Growth**: Assumes a saturating growth pattern and is often more realistic for natural phenomena.

## Requirements

To run this project, you need to install the necessary libraries listed in the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

## Performance Metrics
- **Mean Absolute Error (MAE)**: Measures the average magnitude of the errors in predictions.
- **R-Squared (R²)**: Represents the proportion of variance in the data explained by the model.

## Key Insights:
- The Logistic Growth model provides a more accurate prediction, as it accounts for a saturation point, which is more realistic for sunspot cycles.
- Linear Growth and Flat Growth models are also evaluated for comparison, with the Flat Growth model serving as a baseline.

## Acknowledgments
- The data used in this project is publicly available and can be found in the `sunspot data repository`.
- Special thanks to the Prophet library for making time series forecasting accessible.
