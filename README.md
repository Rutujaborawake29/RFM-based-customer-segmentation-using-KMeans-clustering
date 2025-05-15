# 📊 RFM-based Customer Segmentation using KMeans Clustering

This project demonstrates how to perform **Customer Segmentation** using the **RFM (Recency, Frequency, Monetary)** model combined with **KMeans clustering**. The goal is to group customers based on their purchasing behavior to support targeted marketing strategies.

## 🧠 Project Objectives

* Load and clean an e-commerce dataset.
* Perform **RFM analysis** to calculate:

  * **Recency**: Days since the last purchase.
  * **Frequency**: Total number of purchases.
  * **Monetary**: Total money spent.
* Apply **Standard Scaling** to normalize the data.
* Use **KMeans Clustering** for segmentation.
* Determine optimal clusters using the **Elbow Method**.
* Visualize the clusters.
* Evaluate performance using the **Silhouette Score**.


## 🛠️ Tools & Libraries Used

* **Python**
* **Pandas** – data manipulation
* **NumPy** – numerical operations
* **Matplotlib / Seaborn** – data visualization
* **Scikit-learn** – clustering, preprocessing, and metrics

## 📁 Dataset

* Dataset file: `data.csv`
* Source: E-commerce transactions
* Key fields used: `InvoiceDate`, `CustomerID`, `UnitPrice`, `Quantity`

## 🧼 Data Preprocessing

* Handled missing values in `Description` and `CustomerID`.
* Converted `InvoiceDate` to datetime format.
* Created a new column `TotalPrice = Quantity * UnitPrice`.

## 📈 RFM Feature Engineering

Grouped data by `CustomerID` to calculate:

* **Recency**: Days since the last purchase.
* **Frequency**: Number of invoices.
* **Monetary**: Sum of total spending.

## 🔍 Clustering Steps

1. **Scaling**: Standardized RFM values using `StandardScaler`.
2. **Elbow Method**: Identified optimal number of clusters.
3. **KMeans Clustering**: Chose 7 clusters based on elbow plot.
4. **Silhouette Score**: Used to evaluate cluster cohesion and separation.

## 📊 Visualizations

* **Elbow Plot**: Helps identify the ideal number of clusters.
* **Scatter Plot**: Plots Recency vs Monetary, color-coded by cluster labels.

## ✅ Results

* KMeans clustering successfully segmented customers into 7 clusters.
* Silhouette Score provided a metric to validate the effectiveness of clustering.

## 📌 Future Enhancements

* Use **Hierarchical Clustering** or **DBSCAN** for comparison.
* Visualize clusters in 3D (Recency, Frequency, Monetary).
* Build customer personas for each cluster.
* Implement dashboard in Power BI or Tableau.


## 👤 Author
**Rutuja Borawake**
📧 Email: [rutushali614@gmail.com](mailto:rutushali614@gmail.com) | [rutujaborawake29@gmail.com](mailto:rutujaborawake29@gmail.com)
🔗 [Portfolio Website](https://rutujaborawake-portfolio.com)
🔗 [LinkedIn](https://www.linkedin.com/in/rutuja-borawake)
🔗 [GitHub](https://github.com/Rutujaborawake29)

