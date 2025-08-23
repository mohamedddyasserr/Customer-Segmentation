# Customer-Segmentation
---

## Problem Statement
Businesses often struggle to understand the purchasing behavior of their customers.  
By applying **unsupervised machine learning (K-Means clustering)** on mall customers, we aim to identify distinct groups of buyers.  
This helps in designing **targeted marketing strategies**, improving customer satisfaction, and optimizing business decisions.

---

## Dataset Overview
The dataset used is the **Mall Customer Segmentation Data** from Kaggle.  
It contains **200 customer records** with the following features:

- **Gender**
- **Age**
- **Customer ID**
- **Annual Income (k$)**
- **Spending Score (1–100)**

For this analysis, clustering was primarily performed using **Annual Income** and **Spending Score**.

---

## Data Processing Steps
1. **Data Cleaning**  
   - Checked for missing values (none found).  
   - Converted `Gender` to numerical encoding (0 = Male, 1 = Female).  

2. **Feature Selection**  
   - Focused on `Annual Income` and `Spending Score` for clustering.  

3. **Scaling**  
   - Applied feature scaling where necessary for consistent clustering results.  

---

## Segmentation Approach
1. **Exploratory Data Analysis (EDA)**  
   - Explored distributions of income and spending.  
   - Visualized customer spread in 2D space.  

2. **Choosing Optimal Clusters**  
   - Applied **Elbow Method** (inertia vs. k).  
   - Verified with **Silhouette Scores**.  
   - Final choice: **k = 5** clusters.  

3. **K-Means Clustering**  
   - Segmented customers into 5 groups based on income and spending score.  

---

## Model Outputs
- **Optimal number of clusters: 5**  
- Identified customer groups include:  
  - **Cluster 1**: Low income, low spending  
  - **Cluster 2**: Low income, high spending  
  - **Cluster 3**: Mid income, average spending  
  - **Cluster 4**: High income, low spending  
  - **Cluster 5**: High income, high spending  

These results give a clear segmentation of customer behaviors.  

---

## Visualizations
Here are the main plots used in the analysis:

| **Elbow Method** | **Silhouette Scores** |
|------------------|-------------------------------|
| <img width="500" height="593" alt="image" src="https://github.com/user-attachments/assets/cbd37fb9-b7cb-4d6f-8043-d7a36db7de80" />| <img width="500" height="593" alt="image" src="https://github.com/user-attachments/assets/49e2a3a9-d719-4c1c-a294-bdc14073c5e4" />|



And here is the final **Scatter Plot of Clusters**:

 <img width="893" height="687" alt="image" src="https://github.com/user-attachments/assets/36239f0c-571a-46c0-85f5-caccf620f190" />

---

## Conclusion

  -Customer segmentation was successfully achieved using K-Means clustering.
  
  -The analysis revealed 5 distinct customer groups with varying income and spending behaviors.
  
  -These insights can be used to design targeted marketing strategies (e.g., special offers for high income–low spending group).

---

## Author

<div>
<table align="center">
  <tr>    </td>
    </td>
        <td align="center">
      <a href="https://github.com/mohamedddyasserr" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/126451832?v=4" width="150px;" alt="Mohamed Yasser"/>
        <br />
        <sub><b>Mohamed Yasser</b></sub>
      </a>
    </td>    
  </tr>
</table>
</div>
  
