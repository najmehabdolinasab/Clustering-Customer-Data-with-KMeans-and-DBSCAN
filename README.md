# Clustering-Customer-Data-with-KMeans-and-DBSCAN
A data analysis project that uses KMeans and DBSCAN clustering algorithms to segment customer data. The project includes data preprocessing, handling missing values, and applying clustering techniques to identify customer groups.
# Clustering Customer Data with KMeans and DBSCAN

This project demonstrates the process of clustering customer data using two popular algorithms: KMeans and DBSCAN. The project includes data preprocessing, handling missing values, and applying clustering techniques to identify customer groups.

## Project Description

In this project, the following steps are applied:

1. **Importing Libraries**:
   - Libraries like **Pandas**, **Numpy**, **Seaborn**, **Matplotlib**, **LabelEncoder**, **StandardScaler**, **KMeans**, and **DBSCAN** are imported for data processing, analysis, and clustering.

2. **Loading and Preparing Data**:
   - Data is loaded, and initial exploration is done using methods like:
     - `info()` to get information about data types and missing values.
     - `describe()` to see summary statistics.
     - `head()` to preview the first few rows of data.
   - The data is split into features (X) and target (y), where the target column is assumed to be "Gender."

3. **Handling Missing Values and Preprocessing**:
   - Missing values are handled and features are scaled using **StandardScaler** to normalize the data.

4. **Clustering with KMeans**:
   - The **KMeans** algorithm is applied with `n_clusters=5` to segment the customer data into 5 clusters.
   - Cluster labels are added to the DataFrame.

5. **Clustering with DBSCAN**:
   - The **DBSCAN** algorithm is applied, which automatically determines the number of clusters based on the data density.
   - DBSCAN labels are added to the DataFrame.

6. **Visualization**:
   - Various plots and visualizations are created to analyze the clustering results and to compare the performance of the two algorithms.

This project demonstrates the use of KMeans and DBSCAN for customer segmentation, helping to identify meaningful groups based on customer data.

## Libraries Used
- Pandas
- Numpy
- Seaborn
- Matplotlib
- Scikit-learn (KMeans, DBSCAN, StandardScaler, LabelEncoder)
## How to Use
1. **Clone the repository**:
2.  **Install required libraries**:
3. **Run the code**:
Open the `Market Basket Analysis.ipynb` file in Jupyter Notebook and follow the steps for data preprocessing, clustering, and evaluation.

## Contributing
If you would like to contribute to this project, please feel free to submit a pull request. All suggestions and improvements are welcome!

## How to Use
1. **Clone the repository**:
