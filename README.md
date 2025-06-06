# K-Means Clustering on Mall Customers Dataset

##  Objective

The goal of this project is to apply **K-Means Clustering**, an unsupervised machine learning algorithm, to segment customers based on their annual income and spending score. This can help businesses understand customer behavior and target marketing strategies more effectively.

---

## Tools & Libraries Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

##  Dataset

File:`Mall_Customers.csv`  
Attributes:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

Only numeric attributes (`Age`, `Annual Income`, `Spending Score`) were used for clustering.

---

##  Tasks Performed

1. Data Preprocessing
   - Removed non-numeric columns like `CustomerID` and `Gender`.

2. Elbow Method
   - Used to find the optimal number of clusters (K) by plotting the inertia for different values of K.

3. K-Means Clustering
   - Applied with optimal K (assumed as 5 based on the elbow curve).
   - Cluster labels assigned to each customer.

4. PCA for Visualization
   - Principal Component Analysis (PCA) reduced dimensions to 2D for plotting clusters.

5. Cluster Visualization
   - Color-coded scatter plot of clusters using Seaborn.

6. Model Evaluation
   - Calculated **Silhouette Score** to evaluate clustering performance.

---

##  Results

- Optimal Clusters (K): 5  
- Silhouette Score: ~0.444  
- Visualization: PCA plot of customer segments showing well-separated clusters.

---

##  What i Learned

- Basics of **Unsupervised Learning**
- Implementation of **K-Means Clustering**
- Using the **Elbow Method** and **Silhouette Score**
- Visualizing clusters with **PCA** and **Seaborn**

