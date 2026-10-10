# Data Preprocessing and EDA

## Overview
This notebook demonstrates common data-preprocessing and exploratory data-analysis (EDA) tasks using Python and Pandas. It works with Titanic, California housing, wine-quality, Iris, and student data.

## Files
### Datasets used by the notebook
- `Titanic-Dataset.csv` — missing-value handling, categorical encoding, data-type selection, frequency counts, stratified train/test splitting, and fare distribution.
- `housing.csv` — missing-value checks and descriptive statistics, including skewness and kurtosis.
- `winequalityN.csv` — duplicate detection/removal, Z-score standardization, sampling, standard deviation, and variance.
- `Iris.csv` — column-name normalization, train/test splitting, and boxplot visualization.
- `student-data.csv` — student age summary statistics; the notebook also attempts to calculate BMI if `weight` and `height` columns are present.

### Additional files referenced by optional cells
These filenames are referenced in the notebook, but are not included in the main set of uploaded datasets:
- `titanic_train.csv`
- `titanic_test.csv`
- `students_math.csv`
- `students_portuguese.csv`

The notebook's corresponding cells will report an error if these additional files are not available. The student merge also requires a `school` column in both student files.

## Requirements
- Python 3
- Pandas
- Matplotlib
- scikit-learn
- Google Colab (the notebook includes Google Drive mounting code)

Install the Python libraries if needed:

```bash
pip install pandas matplotlib scikit-learn
```

## How to Run
1. Place the notebook and the five main CSV datasets in the same directory, or upload them to the location expected by the notebook.
2. Open `code.ipynb` in Google Colab or Jupyter Notebook.
3. Update the CSV paths in the notebook if your files are stored elsewhere.
4. Run the cells in order.
5. If running outside Google Colab, remove or adapt the `google.colab` Drive-mount cell.

## Topics Covered
- Inspecting datasets and checking missing values
- Filling missing Titanic passenger ages with the mean
- Detecting and removing duplicate wine records
- Renaming columns to lowercase
- Encoding categorical variables
- Standardizing numerical features with Z-scores
- Selecting categorical and numerical columns
- Sampling records
- Train/test splitting, including stratification by Titanic survival
- Descriptive statistics: mean, median, mode, standard deviation, variance, skewness, and kurtosis
- Frequency counts and visualizations using boxplots and histograms

## Notes
- Dataset column names must match those used in the notebook.
- In the housing statistics cell, the notebook currently references `df_housing.mean`, `df_housing.median`, and `df_housing.mode` without parentheses. Use `df_housing.mean()`, `df_housing.median()`, and `df_housing.mode()` to calculate and display the statistics.
- The BMI calculation only works if `student-data.csv` contains numeric `weight` and `height` columns.
