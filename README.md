# Cryptocurrency-Unsupervised-Learning

## Background

* Created a report that includes what cryptocurrencies are on the trading market and determine whether they can be grouped to create a classification system for this new investment.

* Used several clustering algorithms to explore whether the cryptocurrencies can be grouped together with other similar cryptocurrencies. Generated data visualization to share the findings.

### Data Cleaning and Preprocessing 

* The dataset was obtained from [CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist).

* Discarded all cryptocurrencies that are not being traded. 

* Removed all rows that have at least one null value.

* Filtered for cryptocurrencies that have been mined.

* Converted the remaining features with text values, `Algorithm` and `ProofType`, into numerical data. 

* Standardized the dataset so that columns that contain larger values do not unduly influence the outcome.

![image](https://user-images.githubusercontent.com/90559756/166235910-ded54146-10a9-46e8-9fbd-ae98bc418674.png)

### Dimensionality Reduction

* Performed dimensionality reduction with PCA. 

![image](https://user-images.githubusercontent.com/90559756/166236118-82c9f536-8b4d-48ec-a813-1ae4231020d8.png)

* Further reduced the dataset dimensions with t-SNE and visually inspect the results. Created a scatter plot of the t-SNE output. 

![image](https://user-images.githubusercontent.com/90559756/166236056-dba70d81-85c4-4af2-b338-fbd2b95a9664.png)

### Cluster Analysis with k-Means

* Created an elbow plot to identify the best number of clusters. 

![image](https://user-images.githubusercontent.com/90559756/166236792-29c99a61-e213-4fe0-8bab-20b05ca8dff6.png)

### Recommendation: Can the cryptocurrencies be clustered together? If so, into how many clusters?

Based on the present analyses, the cryptocurrencies cannot be clustered together. After carefully reducing the number of features in teh data and plotting the data to visually inspect for clusters, it is quite clear the cryptocurrencies have no distinct clusters.
