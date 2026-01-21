# Hierarchical-Clustering-using-Mall-Customer
## 📌 Project Overview
This project focuses on **customer segmentation** using **Hierarchical Agglomerative Clustering** on the Mall Customers dataset. The objective is to group customers based on their **annual income** and **spending score**, helping businesses understand purchasing behavior and customer value segments.

---

## 📂 Dataset Description
- **Dataset Name:** Mall_Customers.csv  
- **Each row:** One customer  
- **Features Used for Clustering:**
  - Annual Income (k$)
  - Spending Score (1–100)

The following columns are excluded:
- CustomerID (identifier)
- Age
- Genre (encoded but not used for clustering)

---

## ⚙️ Tools & Libraries Used
- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **SciPy**
- **Matplotlib**
- **Seaborn**

---

## 🔄 Data Preprocessing
- Checked for missing values
- Encoded categorical column **Genre** using Label Encoding
- Selected relevant numerical features
- Prepared clean input data for clustering

---

## 🌳 Hierarchical Clustering Approach
- **Method:** Agglomerative Clustering
- **Distance Metric:** Euclidean
- **Linkage Method:** Average
- **Number of Clusters:** 5

Hierarchical clustering builds clusters step-by-step by merging the closest data points or clusters.

---

## 📐 Dendrogram Analysis
- A **dendrogram** is plotted using Ward’s method
- Helps visualize how clusters are formed
- Used to decide the optimal number of clusters

---

## 📊 Cluster Visualization
- Scatter plot between:
  - Annual Income (k$)
  - Spending Score
- Each cluster is represented using different colors
- Visualized using Seaborn for clarity

---

## 📈 Applications
- Customer behavior analysis
- Targeted marketing strategies
- Identifying high-value and low-value customers
- Business decision support

---

## ✅ Conclusion
This project demonstrates the effectiveness of **hierarchical clustering** in identifying meaningful customer segments. The visual interpretation using dendrograms and scatter plots provides valuable insights into customer purchasing patterns.

---

## 🚀 Future Enhancements
- Compare results with K-Means and DBSCAN
- Add customer profiling for each cluster
- Integrate demographic features
- Deploy clustering insights in dashboards
