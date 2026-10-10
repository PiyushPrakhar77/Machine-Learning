# SVM and Decision Tree Classification

## Overview
This code implements Support Vector Machine (SVM) and Decision Tree classifiers using built-in scikit-learn functions. It covers preprocessing, feature selection, model training, visualization, and evaluation on two datasets.

## Datasets
- `breast-cancer.csv` — Breast Cancer Wisconsin (Diagnostic) dataset for SVM preprocessing and classification.
- `Titanic-Dataset.csv` — Titanic survival dataset for Decision Tree preprocessing and classification.

Update the file paths in the notebook if you rename either dataset.

## Topics Covered

### 1. SVM — Breast Cancer Dataset
- Dataset dimensions and class counts
- Class-count bar plot
- Correlation matrix and heatmap
- Scatter plot of `radius_mean` versus `texture_mean`, colored by class
- Selecting the 10 features most correlated with the target
- 80/20 train-test split
- Training SVM models with linear, polynomial (`poly`), and RBF kernels
- Comparing test accuracy and classification reports
- Visualizing a decision boundary using two features

### 2. Decision Tree — Titanic Dataset
- Selecting `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, and `Embarked`
- Imputing missing values in `Age` and `Embarked`
- Encoding categorical variables
- 80/20 train-test split
- Normalizing numerical features with `MinMaxScaler`
- Training a Decision Tree Classifier with `criterion='gini'` and `max_depth=5`
- Visualizing the tree with `plot_tree`
- Confusion matrix heatmap
- Evaluation using accuracy, precision, recall, and F1-score

## Requirements
- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

Install the libraries with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Run
1. Place `code.ipynb` and both CSV datasets in the same folder, or upload them to Google Colab.
2. Make sure the notebook's dataset paths match the actual filenames.
3. Run the notebook cells in order.

## Author
**Piyush Prakhar**  
