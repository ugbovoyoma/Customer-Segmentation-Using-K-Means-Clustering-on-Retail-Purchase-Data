# 🛍️ Customer Segmentation Using K-Means Clustering on Retail Purchase Data

## 📘 Project Overview

This project focuses on customer segmentation using **K-Means Clustering**, a popular unsupervised machine learning technique. The goal is to group customers based on their purchasing behavior to help businesses better understand their customer base and make data-driven decisions.

As part of my data science learning journey, I explored how clustering algorithms can uncover hidden patterns in retail data and how these insights can drive strategic marketing and operational decisions.

---

## 🧠 Objectives

- Apply K-Means clustering to segment retail customers
- Use PCA for dimensionality reduction and cluster visualization
- Evaluate cluster quality using silhouette score
- Compare K-Means with DBSCAN clustering
- Derive business insights and recommendations

---

## 🗂️ Dataset

- **Type**: Retail customer purchase dataset
- **Features Used**: (e.g., Annual Income, Spending Score, Frequency, etc.)
- **Source**:  https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

> *Note: The data was cleaned and standardized before modeling.*

---

## 🔧 Tools & Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- PCA (Principal Component Analysis)
- K-Means, DBSCAN

---

## 🔍 Methodology

1. **Data Preprocessing**: Standardized the data for clustering.
2. **K-Means Clustering**:
   - Determined optimal `k` using the Elbow Method.
   - Applied clustering and assigned labels.
3. **Dimensionality Reduction**:
   - Used PCA to reduce features to 2D for visualization.
4. **Evaluation**:
   - Calculated silhouette score to assess cluster quality.
   - Compared performance with DBSCAN.
5. **Visualization**:
   - Plotted clusters using PCA components.

---

## 📌 Conclusion

Through this project, I discovered that K-Means effectively segmented customers into meaningful clusters based on purchasing patterns. While I tested DBSCAN as well, K-Means produced clearer, more useful groupings. This hands-on experience reinforced my understanding of unsupervised learning and customer analytics.

---

## 💡 Business Insights

- **High-Value Customers**: A clear segment of high spenders emerged. These customers should be prioritized with loyalty programs and personalized offers.
- **At-Risk Customers**: Some clusters included low-engagement users. Re-engagement strategies could prevent churn in this group.
- **Personalization Potential**: Businesses can leverage these clusters for targeted marketing, product recommendations, and operational efficiency.
- **Future Enhancements**:
  - Incorporate time-series analysis to capture seasonal behavior.
  - Add demographic or geographic data for deeper segmentation.

---

## 📈 Results

- Optimal clusters: 5
- Silhouette Score (K-Means):  0.3850194889047295
- Visualized clusters with PCA
- DBSCAN provided a lower silhouette score, validating the choice of K-Means

