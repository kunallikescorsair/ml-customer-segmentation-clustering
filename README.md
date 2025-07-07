# Customer Segmentation with Clustering

This project applies unsupervised machine learning to identify distinct customer segments based on transaction patterns. It is part of a university assignment (36106 - Machine Learning Applications), focusing on male customers aged 25–50.

## Files

- `eda-customer-2550-male.ipynb` — Exploratory data analysis for the 25–50 male customer group
- `clustering-customer-segmentation.ipynb` — Dimensionality reduction + K-Means clustering
- `requirements.txt` — Required Python libraries

## Workflow Summary

### 1. EDA (`eda-customer-2550-male.ipynb`)
- Cleaned and explored transaction data for male customers aged 25–50
- Analyzed spending patterns, distributions, and outliers
- Normalized relevant features for clustering

### 2. Clustering (`clustering-customer-segmentation.ipynb`)
- Scaled features using `StandardScaler`
- Applied PCA for dimensionality reduction
- Used the Elbow Method to find optimal `k`
- Performed K-Means clustering
- Visualized clusters using Matplotlib and Altair

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook
