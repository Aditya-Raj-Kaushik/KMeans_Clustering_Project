# K-Means Clustering Project

## Overview

This project applies the K-Means clustering algorithm to segment customers based on their demographic data, such as age, income, and credit score. The goal is to identify meaningful customer groups that can be used for targeted marketing or business insights.

## Dataset

The dataset contains the following features:

- **CustomerID**: Unique identifier for each customer.
- **Gender**: Male or Female.
- **Age**: Age of the customer.
- **Income**: Annual income of the customer.
- **Credit Score**: Customer's credit score.

## Usage

1. **Exploratory Data Analysis (EDA):**
   Open `notebooks/01_data_exploration.ipynb` in Jupyter Notebook and analyze the data.

   ```sh
   jupyter notebook notebooks/01_data_exploration.ipynb
   ```

2. **Run K-Means Clustering:**
   Execute the `main.py` script to perform clustering and generate results.

   ```sh
   python main.py
   ```

3. **View Results:**
   Check the `reports/clustering_results.png` for cluster visualizations.

## Methodology

- **Data Preprocessing:** Handling missing values, normalizing features.
- **Choosing Optimal K:** Using the Elbow method and Silhouette Score.
- **K-Means Implementation:** Applying K-Means clustering.
- **Visualization:** Scatter plots and 3D plots to analyze clusters.
- **Insights & Interpretation:** Understanding customer segments.

## Author

**Aditya Raj Kaushik**

