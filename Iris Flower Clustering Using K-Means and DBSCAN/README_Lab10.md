# Iris Clustering with K-Means and DBSCAN

## Overview
This lab applies two unsupervised machine-learning algorithms—K-Means and DBSCAN—to the Iris dataset. It standardizes flower measurements, groups observations into clusters, visualizes the results, and compares the clusters with the known species labels.

## Dataset Required
- `Iris.csv` — the notebook loads this file from `/content/Iris.csv` in Google Colab.

The notebook expects these columns:
- `SepalLengthCm`
- `SepalWidthCm`
- `PetalLengthCm`
- `PetalWidthCm`
- `Species`

The four measurement columns are used as features. `Species` is used afterward to compare the clustering results with the known flower classes; it is not used to train the clustering algorithms.

## Topics Covered
- Loading and inspecting a dataset with Pandas
- Standardizing features with `StandardScaler`
- K-Means clustering with 3 clusters
- Visualizing clusters with scatter plots
- Using the Elbow Method to inspect inertia for different values of K
- Comparing cluster assignments with actual species using a confusion matrix
- DBSCAN clustering with `eps=0.8` and `min_samples=5`
- Counting DBSCAN clusters and noise points
- Experimenting with different DBSCAN `eps` values
- Comparing K-Means and DBSCAN results

## Requirements
- Python 3
- Pandas
- NumPy
- Seaborn
- Matplotlib
- scikit-learn

Install the required libraries:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```

## How to Run
1. Place `SML_Lab10.ipynb` and `Iris.csv` in your working directory, or upload both to Google Colab.
2. Ensure the CSV file is available at `/content/Iris.csv`, or update the path in the notebook.
3. Run the notebook cells in order.

## Notes
- Clustering is unsupervised: cluster numbers do not inherently correspond to species names.
- DBSCAN may label some observations as noise with the label `-1`.
- Results can change with different preprocessing or clustering parameters.

## Author
**Piyush Prakhar**
