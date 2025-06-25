# 📊 Nvidia_Stock_Analysis

This project uses **K-Means clustering** and **unsupervised machine learning** to identify hidden patterns in **NVIDIA’s historical stock data**. The goal is to segment market behavior into meaningful categories such as bullish trends, high volatility periods, and consolidation phases.

---

## 🧠 Overview

Most stock analyses are reactive — this project takes a **data-driven, unsupervised approach** to identify **market regimes** based on raw numerical data (Open, High, Low, Close, Volume).

By applying **K-Means**, **PCA**, and the **Elbow Method**, we uncover distinct behaviors in NVIDIA’s price history — without using any predefined labels.

---

## 📌 Techniques Used

- ✅ Data Preprocessing & Normalization
- 📈 Elbow Method to determine optimal `k` (clusters)
- 🤖 K-Means Clustering (unsupervised ML)
- 🔻 Dimensionality Reduction with PCA for 2D visualization
- 🧩 Cluster interpretation & behavior labeling

---

## 📊 Features

- Clustered stock trading days into:
  - **Bullish Trend**
  - **High Volatility Days**
  - **Consolidation Phase**
- Visualized clusters in:
  - 2D PCA scatter plot
  - Time-series line plot (price vs. time)
- Added business-friendly cluster labels
- Exported final dataset to `nvidia_clustered.csv`

---

---

## 📈 Libraries Used

- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

---

## 🧠 What I Learned

- How to apply unsupervised learning to real-world time-series data
- The power of PCA for visualizing high-dimensional financial features
- Turning raw data into interpretable, actionable insights

---

## 🔗 Let's Connect

Want to collaborate or explore more about this project?  
Feel free to reach out or explore the notebook!

---

## 🏷️ Tags

`#KMeans` `#NVIDIA` `#StockAnalysis` `#MachineLearning` `#UnsupervisedLearning` `#PCA` `#TimeSeries` `#DataScience`
