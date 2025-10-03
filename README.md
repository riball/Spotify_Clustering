Spotify Top Songs Clustering Analysis
Overview
This project analyzes the top Spotify songs dataset using exploratory data analysis (EDA), dimensionality reduction techniques (PCA, t-SNE, UMAP), and clustering algorithms (K-Means, DBSCAN, Agglomerative Clustering). The goal is to uncover trends and patterns in popular music based on features such as energy, danceability, acousticness, and valence.

The results demonstrate the strengths and weaknesses of different dimensionality reduction and clustering methods in grouping songs by their musical characteristics.

Features
Univariate and bivariate exploratory data analysis

Correlation heatmaps and pairwise relationships visualization

Comparison of dimensionality reduction methods: PCA, t-SNE, and UMAP

Clustering with K-Means, DBSCAN, and Agglomerative on reduced embeddings

Cluster interpretability with feature summaries

Insights into popular music trends from clustering results

Dataset
The analysis uses the "Top Spotify Songs" dataset.

Source: Kaggle Spotify Top Songs Dataset
(Download the CSV file and place it in your working directory or upload it to your environment)

Usage
Clone this repository:

bash
git clone https://github.com/yourusername/spotify-clustering.git
cd spotify-clustering
Install dependencies:

bash
pip install -r requirements.txt
Open the Jupyter notebook:

bash
jupyter notebook Spotify_Clustering_Analysis.ipynb
Follow the notebook cells to execute EDA, dimensionality reduction, clustering, and visualization steps.

Requirements
Python 3.7+

Libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn

plotly

umap-learn

These can be installed via:

bash
pip install pandas numpy matplotlib seaborn scikit-learn plotly umap-learn
Methodology Summary
EDA: Explore distributions, relationships, and correlations between musical features.

Dimensionality Reduction: PCA reveals linear variance; t-SNE and UMAP capture complex, nonlinear structure with better separation.

Clustering: K-Means clusters show the clearest groups, especially on UMAP embeddings. DBSCAN struggles due to continuous feature distributions. Agglomerative Clustering shows limited usefulness.

Insights: Popular songs tend to be energetic, danceable, and have positive valence. Acoustic and live songs form distinct minority groups.

Results
PCA components explain limited variance; data is largely nonlinear.

t-SNE and UMAP produce meaningful low-dimensional embeddings with spread-out points.

K-Means clustering on UMAP shows best visual and statistical cluster separation.

Cluster profiles reveal clear feature-based groups (e.g., high energy/danceability vs acoustic/low energy).
