# Linear Regression Fundamentals

A comprehensive Jupyter notebook covering the fundamentals of linear regression.

## Overview

This notebook provides an introduction to linear regression using a restaurant tips dataset. It covers the progression from simple to multiple linear regression, with practical examples and visualizations.

## Topics Covered

- **Simple Linear Regression**: Build simple regression model to predict tips based on total bill
- **Loss Functions & Optimization**: Understand how models learn by minimizing error (MSE, MAE)
- **Multiple Linear Regression**: Incorporate multiple features to improve predictions
- **Handling Categorical Data**: Convert non-numeric features using one-hot encoding
- **Model Evaluation**: Compare different models and understand the accuracy vs interpretability tradeoff

## Dataset

The tutorial uses the classic "tips" dataset from Seaborn, which contains:
- Restaurant bill information
- Tip amounts
- Party size
- Day of week
- Other dining attributes

## Key Concepts Covered

1. **Mathematical Foundation**: Understanding the equation Y = mX + b
2. **Model Training**: Using scikit-learn's LinearRegression
3. **Loss Functions**: Mean Squared Error (MSE) and Mean Absolute Error (MAE)
4. **Feature Engineering**: Creating dummy variables for categorical data
5. **Model Comparison**: Evaluating simple vs complex models

## Requirements

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
scipy
```

## Usage

1. Clone this repository
2. Install the required packages
3. Open `linear_regression.ipynb` in Jupyter Notebook or JupyterLab
4. Run the cells sequentially to follow along with the tutorial

## Key Takeaways

- Linear regression finds the best-fitting line through data points
- More features can improve accuracy but may reduce interpretability
- Model optimization involves minimizing prediction errors
- Real-world applications require balancing accuracy with explainability

