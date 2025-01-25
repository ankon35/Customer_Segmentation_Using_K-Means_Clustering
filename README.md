# Customer Segmentation Using K-Means Clustering

![Customer Clusters](Final%20Output.png)

## Overview

This project performs **customer segmentation analysis** using the **K-Means Clustering algorithm**. Customer segmentation is a crucial task in marketing, enabling businesses to group customers based on their characteristics and behaviors. The insights derived from such clustering help in tailoring personalized marketing strategies.

## Features

- **Dataset Used**: Customer data, including `Annual Income` and `Spending Score`.
- **Methodology**: Implementation of K-Means Clustering to categorize customers into distinct groups based on spending habits and income.
- **Visualization**: A 2D scatter plot displaying customer clusters along with their centroids.
- **Insights**: Identification of key customer segments for targeted marketing.

## Technologies

- **Programming Language**: Python
- **Libraries Used**:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

## Steps in the Analysis

1. **Data Preprocessing**:
   - Imported and cleaned the dataset.
   - Extracted relevant features (`Annual Income` and `Spending Score`).
2. **Optimal Cluster Identification**:
   - Used the **Elbow Method** to determine the optimal number of clusters.
3. **Model Training**:
   - Applied the K-Means Clustering algorithm to segment customers.
   - Assigned cluster labels to the dataset.
4. **Visualization**:
   - Plotted the clusters and their centroids on a 2D scatter plot.

## Insights Gained

The K-Means clustering revealed five distinct customer segments:

1. **Cluster 1**:  
   - **Moderate Income, High Spending**: Active spenders and highly engaged.

2. **Cluster 2**:  
   - **Low Income, Low Spending**: Cost-sensitive customers.

3. **Cluster 3**:  
   - **High Income, High Spending**: Loyal and valuable customers to prioritize.

4. **Cluster 4**:  
   - **High Income, Low Spending**: Untapped potential for upselling opportunities.

5. **Cluster 5**:  
   - **Low Income, Moderate Spending**: Budget-conscious yet active buyers.

These clusters can be leveraged to design **targeted marketing strategies**, such as loyalty programs for high spenders or promotions for cost-sensitive groups.
