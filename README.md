# Spotify Top Songs Clustering Analysis

## Overview

This project analyzes the top Spotify songs dataset using exploratory data analysis (EDA), dimensionality reduction techniques (PCA, t-SNE, UMAP), and clustering algorithms (K-Means, DBSCAN, Agglomerative Clustering). The goal is to uncover trends and patterns in popular music based on features such as energy, danceability, acousticness, and valence.

The results demonstrate the strengths and weaknesses of different dimensionality reduction and clustering methods in grouping songs by their musical characteristics.

---

## Features

- Univariate and bivariate exploratory data analysis
- Correlation heatmaps and pairwise relationship visualization
- Comparison of dimensionality reduction methods: PCA, t-SNE, UMAP
- Clustering with K-Means, DBSCAN, and Agglomerative on reduced embeddings
- Cluster interpretability with feature summaries
- Insights into popular music trends based on clustering results

---

## Dataset

- The dataset used is **Top Spotify Songs**.
- **Source:** [Kaggle Spotify Top Songs Dataset](https://www.kaggle.com/datasets/your-dataset-link)  
  Download the CSV file from Kaggle and place it in your working directory or upload it to your environment.

---

## Usage

1. Clone this repository:

git clone https://github.com/yourusername/spotify-clustering.git
cd spotify-clustering


2. Install dependencies:

pip install -r requirements.txt


3. Launch the Jupyter notebook


4. Follow the notebook cells to run EDA, dimensionality reduction, clustering, and visualization.

---

## Requirements

- Python 3.7+
- Required Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- plotly
- umap-learn

---

## Methodology Summary

- **Exploratory Data Analysis (EDA):** Understand distributions, correlations, and relationships between song features.
- **Dimensionality Reduction:**
  - PCA: Captures linear variance but limited for this dataset.
  - t-SNE and UMAP: Reveal nonlinear structure with better cluster separation.
- **Clustering:**
  - K-Means: Produces the clearest clusters, especially on UMAP embeddings.
  - DBSCAN: Less effective due to continuous feature variation.
  - Agglomerative Clustering: Limited cluster interpretability for this dataset.
- **Insights:**  
  Popular songs generally show high energy, danceability, and positive valence, while acoustic and live performances form smaller, distinct groups.

  

---

## Results

- PCA explains a limited amount of variance indicating non-linear relationships.
- t-SNE and UMAP produce meaningful low-dimensional embeddings with more spread.
- K-Means clustering on UMAP embeddings offers the most interpretable clusters.
- Cluster feature summaries differentiate groups by musical characteristics, e.g., energetic/danceable vs. acoustic.

- <img width="670" height="528" alt="image" src="https://github.com/user-attachments/assets/f5f2cb34-b726-4e1c-bfe9-9002c112c578" />








