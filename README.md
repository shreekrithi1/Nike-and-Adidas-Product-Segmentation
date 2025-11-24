# Nike and Adidas Product Segmentation using Unsupervised Learning

![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-orange)
![License](https://img.shields.io/badge/License-MIT-green)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shreekrithi1/Nike-and-Adidas-Product-Segmentation/blob/main/Nike_and_Adidas_Product_Segmentation.ipynb)

A complete **unsupervised machine learning** project that automatically discovers hidden customer and product segments for **Nike** and **Adidas** using real e-commerce data — no labels needed.

## Project Goal
Apply clustering and dimensionality reduction to answer:
- Which customer segments prefer Nike vs Adidas?
- What are the natural product tiers (premium, mid-range, value)?
- How do price, rating, and review volume shape brand perception?

## Key Findings
- Nike dominates **high-rating, premium-priced** clusters
- Adidas leads in **value-for-money & mid-tier** segments
- 4–5 optimal clusters identified using Elbow Method + Silhouette Score
- Clear brand separation visible in PCA, t-SNE, and UMAP visualizations

## Dataset
Public Nike vs Adidas dataset with ~3,000+ products.

| Feature         | Description                          |
|-----------------|--------------------------------------|
| Product Name    | Name of the product                  |
| Product ID      | Unique identifier                    |
| Brand           | Nike / Adidas                        |
| Category        | Men/Women/Kids, Shoes/Clothing       |
| Listed Price    | Original price (₹)                   |
| Sale Price      | Discounted price (₹)                 |
| Rating          | Average customer rating (1–5)        |
| Reviews         | Number of reviews                    |
| Description     | Product description text             |

## Techniques Used
- Exploratory Data Analysis (EDA)
- Feature Engineering & Standardization
- K-Means Clustering
- Hierarchical (Agglomerative) Clustering
- Optimal cluster selection → Elbow + Silhouette Score
- Dimensionality Reduction → PCA, t-SNE, UMAP
- Visualizations → Matplotlib, Seaborn, Plotly

## Requirements
```bash
pip install pandas numpy scikit-learn matplotlib seaborn plotly wordcloud
