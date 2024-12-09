# Customer Segmentation Using K-Means Clustering

This project applies the **K-Means clustering algorithm** to segment customers into groups based on their annual income and spending score. These insights can help businesses develop personalized marketing strategies and enhance customer satisfaction.

## Overview

Customer segmentation is crucial for understanding customer behavior and optimizing marketing efforts. This project identifies **5 distinct customer groups** using clustering techniques, offering actionable insights to improve business strategies.

## Dataset

The dataset includes customer information such as:
- **Annual Income**
- **Spending Score**

### Preprocessing Steps:
1. Scaled the features to ensure clustering accuracy.
2. Handled missing or inconsistent data.

## Methodology

1. **Data Preprocessing**:
   - Cleaned and standardized the dataset to prepare it for clustering.
2. **Determining the Number of Clusters**:
   - Applied the **Elbow Method** to identify the optimal number of clusters.
3. **Clustering**:
   - Used the **K-Means algorithm** to segment the customers.
4. **Visualization**:
   - Plotted clusters in 2D space to interpret group differences clearly.

## Results

- Customers were grouped into **5 distinct clusters** based on their annual income and spending score.
- Key insights from the clusters:
  - **Cluster 1**: Medium-income customers with moderate spending.
  - **Cluster 2**: High-income customers with high spending (potential premium customers).
  - **Cluster 3**: Low-income customers with low spending (budget-conscious customers).
  - **Cluster 4**: High-income customers with low spending (price-sensitive or savings-focused).
  - **Cluster 5**: Medium-income customers with high spending (value-driven customers).

![Customer Groups](images/customer_groups.png)  
*Visualization of customer clusters and their centroids.*

## Technologies Used

- **Python**: Programming language
- **Libraries**:
  - `numpy`, `pandas` - Data preprocessing and manipulation
  - `scikit-learn` - Machine learning and clustering
  - `matplotlib`, `seaborn` - Data visualization

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation-kmeans.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Customer_Segmentation_using_K_Means_Clustering.ipynb
   ```

## Conclusion

This project demonstrates the use of K-Means clustering to derive meaningful customer segments, providing valuable insights for targeted marketing strategies. The segmentation helps businesses understand their customers better and optimize their offerings accordingly.
