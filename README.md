# customer_segment_Analysis
## 📌 Overview
This project applies **unsupervised machine learning techniques** to segment customers based on their purchasing behavior. The goal is to help businesses better understand customer patterns and optimize marketing strategies.

## 📊 Dataset
- **Source:** Online Retail Dataset (from Kaggle)
- **Features Used:**
  - **CustomerID** → Unique customer identifier
  - **InvoiceDate** → Date of purchase
  - **Quantity** → Number of items purchased
  - **UnitPrice** → Price per unit
  - **TotalPrice** → Computed as `Quantity * UnitPrice`
  - **Recency** → Days since last purchase
  - **Frequency** → Number of transactions per customer
  - **Monetary** → Total spending per customer

## 🛠️ Methods Used
- **Data Preprocessing**
  - Handling missing values
  - Feature engineering (`Recency`, `Frequency`, `Monetary`)
  - Scaling numerical data

- **Clustering Algorithm**
  - **K-Means Clustering** for customer segmentation
  - **Elbow Method** to determine optimal clusters

- **Visualization**
  - **Tableau** used to create **interactive dashboards**
  - **Heatmaps, Scatter Plots, and Pie Charts** to analyze segments
 
   **Results & Insights**
Customers were segmented into 4 clusters based on purchasing patterns.
High-value customers (Cluster X) contribute Y% of total revenue.
Low-engagement customers (Cluster Y) show potential for targeted marketing campaigns.
