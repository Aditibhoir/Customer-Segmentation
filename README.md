# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project applies K-Means Clustering to segment customers of a retail store based on their Annual Income and Spending Score.  
The goal is to help the store target specific customer groups with personalized marketing strategies.

## 📂 Dataset
- Source: [Mall Customers Dataset](https://www.kaggle.com/datasets/shwetabh123/mall-customers)
- File: `Mall_Customers.csv`
- Attributes:
  - `CustomerID` – Unique customer identifier
  - `Genre` – Gender of the customer
  - `Age` – Age of the customer
  - `Annual Income (k$)` – Annual income in thousand dollars
  - `Spending Score (1-100)` – Score assigned based on customer spending behavior

## 🛠️ Steps Performed
1. Data Loading & Exploration
   - Loaded dataset using `pandas`
   - Checked for missing values & basic statistics
2. Feature Selection
   - Selected `Annual Income (k$)` and `Spending Score (1-100)` for clustering
3. Finding Optimal Clusters – Elbow Method
   - Used Within-Cluster Sum of Squares (WCSS) to determine the best number of clusters
4. Applying K-Means Clustering
   - Clustered customers into groups
5. Visualization
   - Plotted Elbow Method graph
   - Created a scatter plot to visualize customer segments
6. Result Summary
   - Saved clustered dataset and cluster summary for further analysis


## 📈 Results
| Cluster | Avg Age | Avg Income (k$) | Avg Spending Score |
|---------|---------|-----------------|--------------------|
| 0       | ~43     | ~55             | ~50                |
| 1       | ~33     | ~87             | ~82                |
| 2       | ~25     | ~26             | ~79                |
| 3       | ~41     | ~88             | ~17                |
| 4       | ~45     | ~26             | ~21                |

Key Insights:
- Cluster 1: High income, high spending – Potential premium customers
- Cluster 3: High income, low spending – Potential to increase engagement
- Cluster 2: Low income, high spending – Value-seeking but active buyers
- Cluster 4: Low income, low spending – Minimal engagement group
- Cluster 0: Moderate income, moderate spending

## 💻 Technologies Used
- Python 3
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## 📬 Contact
Author: Aditi Bhoir  
**GitHub:** [Aditibhoir](https://github.com/Aditibhoir)  

