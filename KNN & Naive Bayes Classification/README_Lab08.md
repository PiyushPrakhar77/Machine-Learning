# Classification Using KNN and Gaussian Naive Bayes

## Overview
This lab demonstrates classification techniques using Python and scikit-learn. It trains a K-Nearest Neighbors (KNN) classifier on the diabetes dataset and a Gaussian Naive Bayes classifier on the Iris dataset, then evaluates the models with classification metrics and confusion-matrix heatmaps.

## Datasets
The notebook references these CSV files:
- `diabetes.csv` — used for KNN classification.
- `Iris.csv` — used for Gaussian Naive Bayes classification.
- `breast-cancer.csv` — loaded in the notebook, but not used in the shown model-training cells.
- `WineQT.csv` — loaded in the notebook, but not used in the shown model-training cells.

Make sure the filenames and file paths in the notebook match your uploaded files. The current code reads from `/content/` in Google Colab. The uploaded diabetes file is named `diabetes(1).csv`, so rename it to `diabetes.csv` or update the code path.

## Topics Covered
- Loading datasets with Pandas
- Train/test splitting
- Feature scaling with `StandardScaler` and `MinMaxScaler`
- K-Nearest Neighbors (KNN), with `K=5`
- Gaussian Naive Bayes
- Confusion matrices and heatmap visualization
- Model evaluation using accuracy, F1-score, recall, and classification reports

## Requirements
- Python 3
- Pandas
- scikit-learn
- Seaborn
- Matplotlib

Install the dependencies:

```bash
pip install pandas scikit-learn seaborn matplotlib
```

## How to Run
1. Place `SML_Lab08.ipynb` and the required CSV files in the same working directory, or upload them to Google Colab.
2. Update the CSV paths in the notebook if needed.
3. Ensure the diabetes dataset is available as `diabetes.csv` at `/content/diabetes.csv`, or modify the path to match its actual filename.
4. Run the notebook cells in order.

## Outputs
- KNN diabetes classification: confusion matrix, accuracy, F1-score, and classification report.
- Iris Gaussian Naive Bayes classification: confusion matrix, accuracy, macro recall, and classification report.

## Author
**Piyush Prakhar**  
Student ID: `S25MCAG0109`
