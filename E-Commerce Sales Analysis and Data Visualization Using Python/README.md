# E-Commerce Sales Analysis and Data Visualization Using Python

## Overview
This project explores e-commerce sales data using Python and visualizes trends in monthly profit and product sales. It also demonstrates statistical visualizations using Seaborn's built-in `tips` dataset.

## Project Files
- `code.ipynb` — Jupyter Notebook containing the analysis and visualizations.
- `ecommerce_data.csv` — Dataset used for the e-commerce sales charts.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Notebook Contents
1. Load and preview the e-commerce dataset.
2. Plot monthly total profit using a line chart.
3. Visualize monthly T-shirt sales using a scatter plot.
4. Compare trouser and shirt sales using a grouped bar chart.
5. Explore the Seaborn `tips` dataset.
6. Create histograms and KDE plots for bills and tips.
7. Compare total bills across days using boxplots and violin plots.
8. Visualize correlations among selected variables with a heatmap.

## Dataset Requirements
The e-commerce CSV is expected to contain these columns:

- `month_number`
- `total_profit`
- `t shirts`
- `trousers`
- `shirts`

## How to Run
1. Upload the notebook and `ecommerce_data.csv` to Google Colab.
2. Ensure the CSV file is in the location referenced by the notebook, or update the file path in the code.
3. Run the notebook cells in order.

To run the notebook locally, install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

If running outside Google Colab, remove or adapt the Google Drive mounting cell.

## Output
The notebook generates visualizations for monthly profit, product sales, bill and tip distributions, total bills by day, and correlations. The sales bar chart is saved as `sales_chart.png`.

## Author
**Piyush Prakhar**  
