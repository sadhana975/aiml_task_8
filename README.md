# 🎯 Customer Segmentation with K-Means Clustering

This project applies **K-Means Clustering** on the **Mall Customers dataset** to segment customers based on their **Annual Income** and **Spending Score**.  
The goal is to identify meaningful customer groups for targeted marketing.

---

## 📂 Dataset
- **Mall_Customers.csv**
- Columns:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## ⚙️ Steps
1. **Load Dataset** using Pandas  
2. **Feature Selection** → Annual Income & Spending Score  
3. **Elbow Method** → Find optimal number of clusters (K)  
4. **Train KMeans** with chosen K (e.g., K=5)  
5. **Cluster Visualization** → Scatter plot with centroids  
6. **Evaluation** → Silhouette Score  
7. **Optional PCA** → Dimensionality reduction for visualization

---

## 📊 Results
- **Optimal K (from Elbow Method):** ~5  
- **Silhouette Score:** `0.554` → Good cluster separation  
- **Visualization:** Clear segmentation of customer groups  

---

## 🖼️ Visualizations
- Elbow curve to select K  
- Customer clusters with centroids  
- PCA projection of clusters  

---

## 🚀 How to Run
```bash
pip install -r requirements.txt
python kmeans_clustering.py
