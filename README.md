# Customer Segmentation using Mall Customer:Data Clustering
# 🛍️ Customer Segmentation Using Mall Customer Data (Clustering)

This project performs customer segmentation using clustering techniques on the Mall Customer Dataset. The goal is to divide customers into distinct groups based on purchasing behavior and demographic features to enable targeted marketing strategies.

---

## 📊 Problem Statement

Businesses often deal with a diverse customer base. By applying clustering algorithms like KMeans and DBSCAN, we can identify **homogeneous groups** within the data and design **personalized marketing campaigns** for each segment.

---

## 📁 Dataset

The dataset contains the following columns:

- **CustomerID**: Unique ID for each customer
- **Gender**: Male or Female
- **Age**: Age of the customer
- **Annual Income (k$)**: Income of the customer in thousands of dollars
- **Spending Score (1–100)**: Score assigned by the mall based on spending behavior

---

## ⚙️ Techniques Used

- **Data Preprocessing**
  - Label encoding (for Gender)
  - Normalization
- **Exploratory Data Analysis (EDA)**
  - Distribution plots
  - Scatter plots
- **Clustering**
  - **KMeans**
    - Elbow Method
    - Silhouette Score
  - **DBSCAN**
    - Density-based clustering with `eps` and `min_samples` tuning
- **Segment Labeling**
  - Manual labels based on income and spending behavior
- **Marketing Strategy Mapping**
  - Each segment is assigned a custom marketing approach

---

## 📈 Cluster Examples

| Cluster | Description                      | Marketing Focus                  |
|---------|----------------------------------|----------------------------------|
| 0       | Moderate Income - High Spenders  | Value-based Premium Offers       |
| 1       | High Income - Low Spenders       | Engagement-Boosting Campaigns    |
| 2       | High Income - High Spenders      | VIP Experiences & Retention      |
| 3       | High Income - Moderate Spenders  | Basket Size Growth Strategies    |
| 4       | Low Income - High Spenders       | Affordable Luxury Promotions     |

---

