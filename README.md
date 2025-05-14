
![HQ graphic](https://github.com/Lanceowesalot/CryptoClustering/blob/main/images/crypto%20squish.jpg).
# 📊 Crypto Clustering Analysis Bootcamp

This project performs clustering analysis on cryptocurrency data using K-means and Principal Component Analysis (PCA). It is designed as part of a Data Analysis Bootcamp to help you explore unsupervised machine learning techniques and visualize cluster behaviors in crypto markets.

---

## 🔗 Table of Contents

- [Overview](#-overview)
- [How to Use](#-how-to-use)
- [Notebook Sections](#-notebook-sections)
  - [Prepare the Data](#prepare-the-data)
  - [K-means Clustering on Original Data](#k-means-clustering-on-original-data)
  - [Principal Component Analysis (PCA)](#principal-component-analysis-pca)
  - [K-means Clustering on PCA Data](#k-means-clustering-on-pca-data)
  - [Compare and Visualize Results](#compare-and-visualize-results)
- [Conclusion](#-conclusion)

---

## 📘 Overview

This notebook explores how clustering algorithms, particularly K-means, can be applied to scaled cryptocurrency market data. It further reduces dimensionality using PCA and re-applies clustering to evaluate performance. The project demonstrates:

- Scaling and preprocessing numeric features
- Elbow method for optimal `k` selection
- Clustering with K-means
- Dimensionality reduction with PCA
- Visualization of cluster outputs

---

## 🛠️ How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/crypto-clustering-bootcamp.git
   cd crypto-clustering-bootcamp
   ```

2. **Install Required Packages**:
   This notebook requires:
   - `pandas`
   - `scikit-learn`
   - `hvplot`
   - `matplotlib`
   - `numpy`

   Install them using pip:
   ```bash
   pip install pandas scikit-learn hvplot matplotlib numpy
   ```

3. **Run the Notebook**:
   Open the notebook in Jupyter:
   ```bash
   jupyter notebook Crypto_Clustering.ipynb
   ```

---

## 📓 Notebook Sections

### Prepare the Data

- Load and clean cryptocurrency market data
- Handle missing values and filter for relevant coins
![HQ graphic](https://github.com/Lanceowesalot/CryptoClustering/blob/main/images/yearly%20change.jpg).

### K-means Clustering on Original Data

- Scale original features
- Use the elbow method to identify the optimal number of clusters
![HQ graphic](https://github.com/Lanceowesalot/CryptoClustering/blob/main/images/original%20elbow.jpg).
- Apply K-means clustering
![HQ graphic](https://github.com/Lanceowesalot/CryptoClustering/blob/main/images/PCA%20Plot.jpg).

### Principal Component Analysis (PCA)

- Reduce the data to principal components
- Analyze how much variance is retained

### K-means Clustering on PCA Data

- Use the reduced dimensions to re-cluster data
- Optimize cluster performance and visualize
![HQ graphic](https://github.com/Lanceowesalot/CryptoClustering/blob/main/images/pca%20plot%20reduced.jpg).

### Compare and Visualize Results

- Plot original vs PCA-based clusters
![HQ graphic](https://github.com/Lanceowesalot/CryptoClustering/blob/main/images/elbow%20comparison.png).
![HQ graphic](https://github.com/Lanceowesalot/CryptoClustering/blob/main/images/cluster%20comparison.jpg).
- Analyze how well PCA improves interpretability and separation

---

## ✅ Conclusion

By the end of this notebook, you will understand how clustering techniques can reveal patterns in crypto market behavior and how PCA can improve performance by reducing noise in the dataset.
