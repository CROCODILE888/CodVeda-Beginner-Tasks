# K-Means Clustering on the Iris Dataset

As part of my Data Science Internship at **Codveda Technologies**, this project applies **K-Means Clustering** to group flowers in the **Iris dataset** into clusters — without using labels.  

---

## **Objectives**
- Apply **K-Means** clustering to unlabeled data.
- Use the **Elbow Method** and **Silhouette Score** to determine the optimal number of clusters.
- Visualize clusters in **2D space using PCA**.
- Compare clustering results with actual species using **Adjusted Rand Index (ARI)**.

---

## **Dataset**
- **Name:** Iris dataset (`sklearn.datasets`)
- **Features:** Sepal length, Sepal width, Petal length, Petal width
- **Target:** 3 Iris species (Setosa, Versicolor, Virginica)

---

## **Key Steps**
1. **Data Preprocessing:**  
   - Standardized features using `StandardScaler` (mean = 0, std = 1).  

2. **Choosing k:**  
   - Used the **Elbow Method** (WCSS vs. k).  
   - Confirmed with the **Silhouette Score** for cluster quality.

3. **Clustering:**  
   - Applied **K-Means** with the chosen number of clusters (k = 3).

4. **Visualization:**  
   - Reduced dimensions to 2D using **PCA**.  
   - Plotted clusters to visually inspect separation.

5. **Evaluation:**  
   - Compared predicted clusters with actual species using **Adjusted Rand Index (ARI)**.

---

## **Results**
- **Optimal Clusters (k):** 3  
- **Adjusted Rand Index:** High alignment with actual species (close to 1.0).  
- **Visualization:** Clear separation between clusters in PCA-reduced space.

---

## **Visuals**
- **Elbow Plot:** To determine optimal k.  
- **Silhouette Scores:** To validate cluster quality.  
- **PCA Scatter Plot:** Visual representation of clusters in 2D.  

---

## **Tools & Libraries**
- Python
- pandas, seaborn, matplotlib
- scikit-learn (KMeans, PCA, metrics)

---

**Author:** Taha Lokhandwala  
**#CodvedaJourney #UnsupervisedLearning #KMeans #MachineLearning #Python**
