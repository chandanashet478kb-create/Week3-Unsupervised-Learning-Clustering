# 📊 Week 3: Unsupervised Learning and Clustering Analysis

## 🎯 Objective
To apply unsupervised machine learning techniques to group customers based on their annual income and spending scores using the K-Means clustering algorithm.

## 📁 Dataset
The Mall Customer Segmentation dataset contains 200 customer records with details such as age, gender, annual income, and spending score.

**Dataset Source:** [Mall Customer Segmentation Dataset](https://raw.githubusercontent.com/hannazan/mall-customer-segmentation/main/data/Mall_Customers.csv)

## 🛠️ Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## 🔍 Steps Performed
1. Loaded and explored the dataset.
2. Checked for missing values and duplicate records.
3. Selected annual income and spending score for clustering.
4. Standardized the selected features using StandardScaler.
5. Applied the Elbow Method to determine the optimal number of clusters.
6. Implemented the K-Means clustering algorithm.
7. Grouped customers into five clusters.
8. Visualized the clusters using graphs.
9. Evaluated clustering performance using the silhouette score.
10. Analyzed the characteristics of each customer segment.

## 📈 Results
- **Total Customers:** 200
- **Number of Clusters:** 5
- **Silhouette Score:** 0.555
- **Largest Cluster:** Cluster 0, containing 81 customers.

The analysis identified five customer segments with different income and spending patterns.

## 📂 Project Files
- `Week3_Customer_Segmentation.ipynb` – Notebook containing the complete implementation and analysis.
- `cluster_analysis.csv` – Summary of the customer clusters.
- `mall_customers_clustered.csv` – Customer dataset with assigned cluster labels.

## 💡 Key Learnings
- Understanding unsupervised machine learning.
- Performing data preprocessing and feature scaling.
- Applying K-Means clustering.
- Using the Elbow Method to select the number of clusters.
- Evaluating clusters using the silhouette score.
- Visualizing and interpreting customer segments.

## ✅ Conclusion
This project demonstrates how K-Means clustering can be used to segment customers based on their income and spending behaviour. The results can help businesses understand customer groups and explore targeted marketing strategies.

## 👩‍💻 Author
Chandana K B
