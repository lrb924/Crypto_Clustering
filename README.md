# Crypto Clustering

### Package Requirments

`pip install x` where x is the below listed packages
* pandas
* hvPlot
* scikit-learn

### Purpose of Use
* Use pandas to combine financial Python programming skills with unsupervised learning skills to create a Jupyter notebook that clusters cryptocurrencies by their performance in different time periods.
* The analysis is in six parts:
  
  1. Investigate Provided CSV File Using Pandas
     1. Create dataframes in order to plot the provided data, and manipulate further in order to prepare.
  2. Find the Best Value for k by Using the Original Data
     1. Use the elbow method to find the best value for k by using the original data.
  3. Cluster the Cryptocurrencies with K-Means by Using the Original Data
     1. Use the K-means algorithm and best value for k to cluster the cryptocurrencies according to the provided price changes of the cryptocurrencies provided.
  4. Optimize the Clusters with Principal Component Analysis
     1. Perform PCA and reduce the features to three principal components.
  5. Find the Best Value for k by Using the PCA Data
     1. Use the elbow method to find the best value for k by using the PCA data.
  6. Cluster the Cryptocurrencies with K-means by Using the PCA Data
     1. Use the PCA data, the K-means algorithm, and the best value for k to cluster the cryptocurrencies according to the principal components.

### Files Navigation
* `crypto_investments.ipynb`: Notebook containing all data analysis and visualization
* `crypto_market_data.csv`: Provided csv file containing crypto market data used in Notebook

### Solution
After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?
* By using fewer features (PCA data), comparatively the clusters appear more obvious and the irrelevant noise was removed.
