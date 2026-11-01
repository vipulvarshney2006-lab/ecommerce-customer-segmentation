# E-Commerce Customer Segmentation Using Machine Learning

## Project Overview

This project focuses on segmenting e-commerce customers based on their purchasing behaviour using Machine Learning techniques.

RFM (Recency, Frequency, Monetary) analysis is used to understand customer behaviour and identify different customer groups.

K-Means and DBSCAN clustering algorithms are applied to identify customer segments. PCA and t-SNE are used for dimensionality reduction and visualization.

## Objectives

- Analyze customer purchasing behaviour.
- Perform RFM analysis.
- Apply K-Means clustering.
- Apply DBSCAN clustering.
- Reduce dimensions using PCA.
- Visualize customer segments using t-SNE.
- Identify customer personas.
- Suggest marketing strategies for different customer groups.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Machine Learning Algorithms

### 1. K-Means
Used to divide customers into different groups based on their RFM values.

### 2. DBSCAN
Used to identify dense customer groups and detect outliers.

### 3. PCA
Used to reduce the dimensions of customer data.

### 4. t-SNE
Used to visualize customer clusters in two dimensions.

## RFM Analysis

- Recency: Number of days since the customer's last purchase.
- Frequency: Number of unique orders placed by the customer.
- Monetary: Total amount spent by the customer.

## Customer Personas

The project aims to identify customer groups such as:

- Champions
- Loyal Customers
- Potential Customers
- At-Risk Customers

Marketing strategies are suggested for each group to improve customer engagement and retention.

## Project Structure

```text
ecommerce-customer-segmentation/
│
├── dataset/
├── notebook/
├── results/
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run

1. Clone this repository.
2. Install the required libraries.
3. Open the Jupyter Notebook in Google Colab.
4. Load the transaction dataset.
5. Run the notebook cells in order.

## Dataset

The project uses the Online Retail dataset from the UCI Machine Learning Repository.

Dataset: https://archive.ics.uci.edu/dataset/352/online+retail

A smaller sample dataset can also be used for testing.

## Results

The project generates customer clusters, dimensionality reduction visualizations, cluster summaries and marketing recommendations.

## Conclusion

This project demonstrates how unsupervised machine learning can help e-commerce businesses understand customer behaviour and develop targeted marketing strategies.

By combining RFM analysis with K-Means and DBSCAN, businesses can identify valuable customers, improve customer retention and create personalized marketing campaigns.

---

**Project Type:** Machine Learning / Unsupervised Learning

**Environment:** Google Colab

**Language:** Python
