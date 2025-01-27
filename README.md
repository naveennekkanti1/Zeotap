# Data Science Assignment: eCommerce Transactions Dataset

## Overview
This repository contains solutions for the Data Science assignment involving eCommerce transactions. The assignment includes three tasks:
1. *Exploratory Data Analysis (EDA) and Business Insights*
2. *Lookalike Model*
3. *Customer Segmentation/Clustering*

Each task is implemented in Python, with results and insights saved as deliverables.

---

## Task 1: Exploratory Data Analysis (EDA) and Business Insights

### Description
This task involves analyzing the provided dataset to identify trends, patterns, and actionable insights.

### Steps Performed:
1. *Data Loading*: Combined Customers.csv, Products.csv, and Transactions.csv.
2. *Key Insights*:
   - Identified the most popular products.
   - Analyzed revenue distribution across regions.
   - Explored monthly sales trends.
   - Highlighted top-spending customers.
   - Categorized revenue by product categories.
3. *Visualizations*:
   - Bar plots, line charts, and pie charts for data trends.

### Deliverables:
- A Python script (Task1_EDA.py) for EDA.
- A PDF report summarizing business insights.

---

## Task 2: Lookalike Model

### Description
This task builds a recommendation system that suggests the top 3 similar customers for each of the first 20 customers based on their profile and transaction history.

### Steps Performed:
1. *Data Aggregation*:
   - Combined customer profiles and aggregated transaction data.
2. *Feature Engineering*:
   - Encoded categorical variables and scaled features.
3. *Model Development*:
   - Used cosine similarity to calculate customer similarities.
   - Recommended top 3 similar customers for the first 20 customers.
4. *Output*:
   - Generated a CSV file (Nekkanti_DurgaNaveen_Lookalike.csv) containing similarity scores.

### Deliverables:
- A Python script (Task2_Lookalike_Model.py) explaining the model development.
- A CSV file (Nekkanti_DurgaNaveen_Lookalike.csv) with recommendations.

---

## Task 3: Customer Segmentation/Clustering

### Description
This task performs customer segmentation using clustering techniques, combining profile and transaction information.

### Steps Performed:
1. *Data Preparation*:
   - Merged Customers.csv and aggregated Transactions.csv.
   - Encoded categorical features and scaled data.
2. *Clustering*:
   - Applied K-Means clustering (4 clusters).
   - Evaluated clusters using Davies-Bouldin Index (DB Index) and Silhouette Score.
3. *Visualization*:
   - Reduced data dimensions using PCA and visualized clusters.
4. *Output*:
   - Saved cluster labels in Clustering_Results.csv.

### Deliverables:
- A Python script (Task3_Clustering.py) for clustering.
- A CSV file (Clustering_Results.csv) with cluster labels.
- A report summarizing clustering metrics and visualizations.

---

## Prerequisites
Ensure you have the following installed:
- Python (>= 3.8)
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Install the required libraries using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
