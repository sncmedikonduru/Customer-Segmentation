
# Customer Segmentation using Unsupervised Machine Learning

## Project Overview
This project focuses on segmenting customers into distinct groups using unsupervised machine learning techniques. By leveraging clustering algorithms, businesses can better understand customer behavior and design tailored marketing strategies.

## Objectives
- Perform data preprocessing and feature engineering on the dataset.
- Apply unsupervised machine learning algorithms for customer segmentation:
  - Principal Component Analysis (PCA) for dimensionality reduction.
  - Clustering techniques: K-Means, Hierarchical Clustering, DBSCAN, and Gaussian Mixture Models (GMM).
- Visualize and interpret cluster characteristics for actionable insights.

## Dataset
- The dataset used is a credit card dataset containing customer information, including balance, purchases, payments, and credit limits.
- Example features:
  - `BALANCE`: Average balance on the credit card.
  - `PURCHASES`: Total purchase amount.
  - `CREDIT_LIMIT`: Credit limit of the customer.

## Steps in the Project
### 1. Data Preprocessing
- Handled missing values by imputing with column means.
- Scaled the dataset using `StandardScaler` to standardize numeric values.

### 2. Dimensionality Reduction
- Applied PCA to reduce dimensionality while retaining 95% of the variance.

### 3. Clustering Algorithms
- **K-Means Clustering:**
  - Used the Elbow Method and Silhouette Score to determine the optimal number of clusters.
- **Hierarchical Clustering:**
  - Visualized clusters using a dendrogram and applied agglomerative clustering.

### 4. Visualization and Cluster Analysis
- Visualized clusters in PCA-reduced space using scatter plots.
- Analyzed and compared cluster characteristics using bar plots and descriptive statistics.

## Results
- Customers were segmented into distinct groups based on spending and payment behavior.
- Insights from clusters can guide marketing strategies, customer retention efforts, and product recommendations.

## Tools and Libraries
- Python
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## How to Run
1. Clone this repository.
2. Install required Python libraries using:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook or Python script provided.


## License
This project is licensed under the MIT License.
