# Mall Customer Segmentation Using Machine Learning

## Project Overview

This project applies unsupervised machine learning techniques to segment mall customers according to their annual income and spending behavior.

K-Means and DBSCAN clustering algorithms are implemented to identify customer groups and understand their purchasing patterns.

## Project Objectives

- Explore and analyze customer shopping data.
- Perform Exploratory Data Analysis (EDA).
- Clean and preprocess the dataset.
- Apply feature standardization.
- Identify customer groups using K-Means clustering.
- Apply DBSCAN to detect clusters and noise points.
- Determine cluster quality using the Silhouette Score.
- Visualize clusters using PCA and t-SNE.
- Interpret customer segments based on income and spending patterns.

## Dataset

**Dataset:** Mall Customers Dataset

**File:** `Mall_Customers.csv`

The dataset typically contains the following attributes:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

The main clustering features are:

- Annual Income (k$)
- Spending Score (1-100)

## Technologies and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Methodology

### 1. Data Loading

Loaded the Mall Customers dataset using Pandas.

### 2. Exploratory Data Analysis

- Examined dataset structure and statistical information.
- Checked missing values and duplicate records.
- Visualized gender distribution.
- Analyzed customer age.
- Explored annual income and spending score distributions.

### 3. Data Preprocessing

- Removed duplicate records.
- Handled missing numerical and categorical values.
- Selected annual income and spending score as clustering features.
- Applied StandardScaler to standardize the selected features.

### 4. K-Means Clustering

- Used the Elbow Method to investigate the optimal number of clusters.
- Applied K-Means with five clusters as the initial configuration.
- Visualized the resulting customer groups.

### 5. DBSCAN Clustering

- Applied DBSCAN to identify density-based customer groups.
- Identified noise points and outliers.
- Visualized the resulting clusters.

### 6. Model Evaluation

Evaluated clustering quality using the Silhouette Score.

The K-Means and DBSCAN results are compared where a valid silhouette score can be calculated.

### 7. Dimensionality Reduction

Applied:
- Principal Component Analysis (PCA)
- t-Distributed Stochastic Neighbor Embedding (t-SNE)

These techniques help visualize customer clusters in two dimensions.

### 8. Customer Segment Interpretation

Analyzed average customer age, annual income, and spending score for each K-Means cluster.

Possible customer segments include:

- Premium Customers
- Potential Customers
- Frequent Spenders
- Low-Engagement Customers
- Average Customers

Actual segment interpretations depend on the calculated cluster averages.

## How to Run the Project

1. Open Google Colab.
2. Upload or open `notebook.ipynb`.
3. Upload the `Mall_Customers.csv` dataset when prompted.
4. Run all notebook cells in sequence.
5. Review the clustering visualizations and evaluation results.
6. Download the generated `Mall_Customer_Segmentation_Results.csv` file.

## Project Files

- `notebook.ipynb` – Complete implementation, analysis, and visualizations.
- `README.md` – Project documentation.
- `requirements.txt` – Required Python libraries.

## Results

The notebook generates actual clustering results, Silhouette Scores, customer segment summaries, and visualizations during execution. No performance values are assumed or hardcoded.

## Conclusion

This project demonstrates how unsupervised machine learning can help identify customer groups based on income and spending behavior. These insights can support customer profiling, marketing strategies, and business decision-making.

## Author

Developed as part of an Artificial Intelligence and Machine Learning internship.
