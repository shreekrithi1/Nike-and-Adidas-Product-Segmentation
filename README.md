Nike and Adidas Product Segmentation
Python
License
Unsupervised Learning
Open In Colab
A real-world unsupervised machine learning project that automatically segments Nike and Adidas products and customers using clustering — no labels required.
Project Objective
Discover hidden customer segments and product groupings by applying K-Means, Hierarchical Clustering, PCA, t-SNE, and UMAP on real Nike & Adidas e-commerce data.
Key business questions answered:

Which customer segments prefer Nike vs Adidas?
What are the premium, mid-tier, and value-for-money product clusters?
How do price, rating, and review volume drive brand perception?

Key Findings

Nike dominates high-rating, premium-priced clusters
Adidas leads in value-for-money & mid-range segments
4–5 natural customer clusters emerge using the Elbow + Silhouette method
Clear separation visible in 2D/3D visualizations (PCA & t-SNE)

Dataset
Public Nike vs Adidas dataset (~3,000+ products) with the following features:













































ColumnDescriptionProduct NameName of the productProduct IDUnique IDBrandNike / AdidasCategoryMen/Women/Kids, Shoes/ClothingListed PriceOriginal price (₹)Sale PriceDiscounted price (₹)RatingAverage rating (out of 5)ReviewsNumber of customer reviewsDescriptionProduct description text
Techniques Used

Exploratory Data Analysis (EDA)
Feature Engineering & Scaling
K-Means Clustering
Hierarchical (Agglomerative) Clustering
Optimal clusters → Elbow Method + Silhouette Score
Dimensionality Reduction: PCA, t-SNE, UMAP
Rich visualizations with Matplotlib, Seaborn & Plotly

Requirements
txtpandas
numpy
scikit-learn
matplotlib
seaborn
plotly
wordcloud
Install with:
Bashpip install pandas numpy scikit-learn matplotlib seaborn plotly wordcloud
Quick Start
Option 1: Run in Google Colab (Recommended)
Open In Colab
Option 2: Local
Bashgit clone https://github.com/shreekrithi1/Nike-and-Adidas-Product-Segmentation.git
cd Nike-and-Adidas-Product-Segmentation
jupyter notebook "Nike_and_Adidas_Product_Segmentation.ipynb"
Project Structure
text├── Nike_and_Adidas_Product_Segmentation.ipynb   ← Main notebook (full analysis)
├── data/                                        ← Dataset folder (if added)
├── README.md                                    ← You are here
└── requirements.txt                             ← Dependencies
