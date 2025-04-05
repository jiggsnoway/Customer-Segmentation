# 🧠 Customer Segmentation with K-Means Clustering

This project applies **Unsupervised Machine Learning** to segment customers based on their **Annual Income** and **Spending Score** using **K-Means Clustering**.

---

## 📊 Problem Statement

Businesses need to understand their customers better to create targeted marketing strategies. This project solves that by dividing customers into different **clusters** based on their spending patterns and income, allowing for efficient and personalized marketing.

---

## 🔍 Project Goals

- Segment customers into distinct groups using K-Means clustering.
- Visualize customer distribution based on income and spending.
- Assign each customer to a cluster (group) for analysis.

---

## 🧰 Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **scikit-learn (KMeans)**

---

## 🧪 Steps Involved

1. **Data Preprocessing**:
   - Loaded the dataset using Pandas.
   - Selected only `Annual Income` and `Spending Score` features.

2. **Choosing Optimal Number of Clusters (Elbow Method)**:
   - Used WCSS (Within Cluster Sum of Squares) to find the best number of clusters.
   - Plotted Elbow Curve to choose ideal `k`.

3. **Model Training**:
   - Applied `KMeans` algorithm on the data.
   - Grouped customers into `k` clusters.

4. **Visualization**:
   - Visualized clusters using different colors.
   - Marked centroids with a unique color.

5. **Cluster Assignment**:
   - Added a new column to the dataset showing the cluster each customer belongs to.

---

## 📈 Results

- Grouped customers into 5 distinct clusters.
- Clearly identified patterns based on income and spending.
- Useful for businesses to **identify high-value customers**, **target potential spenders**, and **optimize campaigns**.

---


## 📁 Files Included

- `customer_segmentation.ipynb` 
- `customer_data.csv` - Dataset
- `README.md` - Project overview 

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgments

Thanks to Mall Customer Segmentation dataset available on [Kaggle](https://www.kaggle.com/datasets).

---

## 🚀 Future Ideas

- Use more features like Age, Gender.
- Try different clustering algorithms like DBSCAN or Hierarchical Clustering.

---

### 💫 Made with love by Jigyashman Hazarika

