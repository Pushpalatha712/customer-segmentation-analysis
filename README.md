# customer-segmentation-analysis
# 🧠 Customer Segmentation Analysis using K-Means Clustering

This project performs **customer segmentation** using K-Means clustering on a dataset containing customer demographics and purchase behavior

## 📊 Project Objectives

- Group customers into meaningful segments based on their behaviors.
- Identify patterns such as high-value customers, budget-conscious shoppers, etc.
- Visualize clusters using scatter plots.
- Provide actionable insights for targeted marketing strategies.

## 🗂️ Dataset Overview

The dataset includes the following columns:

| Column               | Description                                      |
|----------------------|--------------------------------------------------|
| `id`                 | Unique Customer ID                               |
| `age`                | Age of the customer                              |
| `gender`             | Gender (Male/Female/Other)                       |
| `income`             | Annual income of the customer                    |
| `spending_score`     | Internal score indicating spending behavior      |
| `membership_years`   | Years since the customer joined                  |
| `purchase_frequency` | Average monthly purchase frequency               |
| `preferred_category` | Most shopped product category                    |
| `last_purchase_amount` | Amount spent in the last transaction           |

## 🛠️ Technologies Used

- Python 3
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## 🚀 How to Run

1. Make sure the dataset file is named:  
   **`customer_segmentation_data.csv`**

2. Run the script:

```bash
python customer_segmentation_analysis.py

 *Steps Performed
*Data Loading & Cleaning
No missing values are present in the dataset.

*Preprocessing

Standard scaling of numerical features

One-hot encoding of categorical features

*Elbow Method
Used to determine the optimal number of clusters (k).

*K-Means Clustering
Segmented customers into meaningful clusters.

*Visualization
Scatter plots to show cluster distributions.

*Insights

Average income/spending per cluster

High-value vs low-engagement segments

📈 Sample Output
Visual Elbow curve to determine k

Cluster plot: income vs. spending score

Segment statistics for each cluster

✅ Future Enhancements
Use PCA for better 2D visualization

Apply DBSCAN or Hierarchical Clustering

Build customer persona profiles
