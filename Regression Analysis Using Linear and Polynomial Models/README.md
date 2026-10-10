# Regression Analysis: Bluegills and NIFTY Indices

## Overview
This notebook explores linear and polynomial regression using two analysis tasks:
1. Modeling the relationship between bluegill fish age and length.
2. Studying the relationship between Bank Nifty and Energy Nifty opening prices.

## Datasets
- `bluegills.txt` — fish age and length data for regression analysis.
- `NIFTY BANK.csv` — Bank Nifty index data; opening prices are used.
- `NIFTY ENERGY.csv` — Energy Nifty index data; opening prices are used.
- `NIFTY 50.csv` — included in the project files, but not required for the two analyses described above.
- `NIFTY MIDCAP.csv` — included in the project files, but not required for the two analyses described above.

## Methods and Metrics
- Linear regression
- Polynomial regression with degrees 1 through 10
- Train/test split
- Training and testing RMS error comparison
- Mean Squared Error (MSE)
- R-squared (R²)
- Visualizations of fitted regression models and index relationships

## Requirements
- Python 3
- Pandas
- NumPy
- Matplotlib
- scikit-learn

Install the libraries with:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## How to Run
1. Place `code.ipynb` and the dataset files in the same folder, or upload them to Google Colab.
2. Update the file paths in the notebook if your datasets are stored elsewhere.
3. Run the notebook cells in order.

## Expected Results
The notebook fits regression models to the bluegills data, compares model errors across polynomial degrees, and evaluates the relationship between Bank Nifty and Energy Nifty opening prices using regression metrics and plots.

## Author
**Piyush Prakhar** 
