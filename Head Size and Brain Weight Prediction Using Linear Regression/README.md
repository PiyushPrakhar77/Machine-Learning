# Head Size and Brain Weight Prediction

## Overview
This demonstrates simple linear regression using the Head Brain dataset. It explores the relationship between head size and brain weight, first calculating the regression line manually and then using scikit-learn's `LinearRegression`.

## Dataset
- `headbrain.csv` — contains head-size and brain-weight measurements.
- The notebook uses the columns `Head Size(cm^3)` and `Brain Weight(grams)`.

## Topics Covered
- Loading data with Pandas
- Descriptive statistics with `describe()`
- Checking and handling missing values
- Splitting data into training and testing sets
- Calculating linear-regression slope and intercept manually
- Plotting actual data and the regression line
- Predicting brain weight
- Evaluating predictions with RMSE and R-squared
- Comparing manual regression with scikit-learn's `LinearRegression`

## Requirements
- Python 3
- Pandas
- NumPy
- Matplotlib
- scikit-learn

Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## How to Run
1. Place `code.ipynb` and `headbrain.csv` in the same working directory, or upload both to Google Colab.
2. In Google Colab, ensure `headbrain.csv` is available at `/content/headbrain.csv`, as expected by the notebook.
3. Run the notebook cells in order.

## Output
The notebook prints descriptive statistics, regression coefficients, predictions, RMSE, and R-squared values. It also plots head size against brain weight with a fitted regression line.

## Author
**Piyush Prakhar**  
