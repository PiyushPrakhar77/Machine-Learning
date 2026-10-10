# Diabetes Prediction Using Logistic Regression

## Overview
This lab builds a binary classification model to predict the diabetes outcome using selected health-related features from `diabetes.csv`.

## Dataset
- `diabetes.csv` — dataset used to train and evaluate the model.
- Target column: `Outcome`
- Features: `Pregnant`, `BP`, `Insulin`, `BMI`, `Pedigree`, and `Age`

The notebook renames selected columns:
- `Pregnancies` → `Pregnant`
- `BloodPressure` → `BP`
- `SkinThickness` → `skin`
- `DiabetesPedigreeFunction` → `Pedigree`

## Methods
1. Load and preview the dataset with Pandas.
2. Display descriptive statistics using `describe()`.
3. Split data into 80% training and 20% testing sets.
4. Visualize BMI versus Age, with points colored by `Outcome`.
5. Standardize features using `StandardScaler`.
6. Train a logistic regression classifier.
7. Evaluate predictions with a confusion matrix, accuracy, F1-score, and classification report.

## Requirements
- Python 3
- Pandas
- scikit-learn
- Matplotlib
- Seaborn

Install dependencies:

```bash
pip install pandas scikit-learn matplotlib seaborn
```

## How to Run
1. Upload `S25MCAG0109_Lab07.ipynb` and `diabetes.csv` to Google Colab, or place them in your local project directory.
2. In Google Colab, the notebook expects the dataset at `/content/diabetes.csv`. Update the path if needed.
3. Run the notebook cells in order.

## Notes
This is an educational machine-learning exercise, not a medical diagnostic tool. Model performance depends on the dataset and the selected features.

## Author
**Piyush Prakhar**  
Student ID: `S25MCAG0109`
