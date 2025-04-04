# 🎯 Customer Segmentation using K-Means Clustering

This project performs **customer segmentation** using the **K-Means clustering algorithm**, an unsupervised machine learning technique. It helps businesses categorize customers based on features like age, income, and spending behavior for more personalized marketing strategies and improved customer experience.

---

## 📖 Overview

Customer segmentation allows businesses to divide their customer base into distinct groups with similar characteristics. This project uses **K-Means clustering** to segment customers based on numerical data like:

- Age
- Annual Income
- Spending Score

We identify patterns that can be used to build targeted campaigns and enhance decision-making.

---

## 🛠 Tech Stack

- **Language**: Python
- **Libraries**:
  - `pandas` – for data handling
  - `numpy` – for numerical operations
  - `matplotlib` & `seaborn` – for data visualization
  - `scikit-learn` – for machine learning (K-Means algorithm)

---

## 🔍 K-Means Clustering

**Steps Followed:**

1. **Data Exploration & Cleaning**
   - Loaded the dataset
   - Handled nulls and checked distributions

2. **Feature Selection**
   - Chose features like `Annual Income` and `Spending Score` for clustering

3. **Finding Optimal Clusters**
   - Used the **Elbow Method** to find the best `k` value

4. **Model Training**
   - Applied `KMeans` from `sklearn.cluster`

5. **Visualization**
   - Plotted clusters to visualize customer segments
