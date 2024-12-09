# Customer Segmentation Using K-Means Clustering

This project applies the **K-Means clustering** algorithm to segment customers into distinct groups based on their **Annual Income** and **Spending Score**. The insights derived from these segments can help businesses create personalized marketing strategies and improve overall customer satisfaction.

## Overview

Customer segmentation is an essential task in understanding customer behavior, enabling businesses to tailor their marketing efforts for maximum impact. This project uses clustering techniques to identify **5 distinct customer groups**, providing actionable insights that can help businesses optimize their strategies.

## Dataset

The dataset used in this project includes customer information with the following features:

- **CustomerID**: Unique identifier for each customer
- **Gender**: Customer's gender
- **Age**: Customer's age
- **Annual Income (k$)**: Annual income of the customer in thousands of dollars
- **Spending Score (1-100)**: A score assigned to the customer based on their spending behavior

## Preprocessing Steps

- **Scaling**: The features `Annual Income` and `Spending Score` were scaled using **StandardScaler** to ensure that clustering results are not biased by differing feature scales.
- **Data Cleaning**: The dataset was checked for missing values, and no missing data was found, ensuring accurate clustering.

## Methodology

### 1. **Data Preprocessing**:
   - The dataset was cleaned and standardized, preparing it for clustering.
   - The relevant features for clustering, `Annual Income (k$)` and `Spending Score (1-100)`, were selected for the K-Means algorithm.

### 2. **Determining the Number of Clusters**:
   - The **Elbow Method** was applied to determine the optimal number of clusters. Based on the Within-Cluster Sum of Squares (WCSS), 5 clusters were identified as the best fit.

### 3. **Clustering**:
   - The **K-Means** algorithm was applied with the optimal number of clusters (5) to segment the customers into groups based on their income and spending behavior.

### 4. **Visualization**:
   - The clusters were visualized in a 2D space to help interpret the differences between the groups clearly.
   - Additionally, **Principal Component Analysis (PCA)** was used to reduce the dimensionality and provide a better understanding of the data distribution in 2D.

## Results

The customers were grouped into 5 distinct clusters, with the following key insights:

- **Cluster 1**: Medium-income customers with moderate spending.
- **Cluster 2**: High-income customers with high spending (potential premium customers).
- **Cluster 3**: Low-income customers with low spending (budget-conscious customers).
- **Cluster 4**: High-income customers with low spending (price-sensitive or savings-focused).
- **Cluster 5**: Medium-income customers with high spending (value-driven customers).

These clusters provide a foundation for businesses to personalize marketing strategies, identify premium customers, target value-driven groups, and tailor promotions to specific customer segments.

## Technologies Used

- **Python**: Programming language for data analysis and machine learning.
- **Libraries**:
  - `numpy`, `pandas`: For data preprocessing and manipulation.
  - `scikit-learn`: For implementing the K-Means clustering algorithm and PCA.
  - `matplotlib`, `seaborn`: For data visualization.

## How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/KaifArman/customer-segmentation-kmeans.git
   ```

2. **Install the Required Libraries**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook Customer_Segmentation_using_K_Means_Clustering.ipynb
   ```

## Conclusion

This project demonstrates the use of **K-Means clustering** to derive meaningful **customer segments**, offering valuable insights that can help businesses optimize their marketing strategies. By understanding customer profiles based on income and spending behavior, businesses can design targeted campaigns and improve customer engagement.
