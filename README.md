# Cryptocurrency-Unsupervised-Learning

## Background

* Created a report that includes what cryptocurrencies are on the trading market and determine whether they can be grouped to create a classification system for this new investment.

* Used several clustering algorithms to explore whether the cryptocurrencies can be grouped together with other similar cryptocurrencies. Generated data visualization to share the findings.


### Data Cleaning and Preprocessing 

* The dataset was obtained from [CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist).

* Discarded all cryptocurrencies that are not being traded. 

* Removeed all rows that have at least one null value.

* Filtered for cryptocurrencies that have been mined.

* Converted the remaining features with text values, `Algorithm` and `ProofType`, into numerical data. 

* Standardizeed the dataset so that columns that contain larger values do not unduly influence the outcome.

### Dimensionality Reduction

* Performed dimensionality reduction with PCA. 

* Further reduced the dataset dimensions with t-SNE and visually inspect the results. Created a scatter plot of the t-SNE output. 

### Cluster Analysis with k-Means

* Createed an elbow plot to identify the best number of clusters. 

### Recommendation: Can the cryptocurrencies be clustered together? If so, into how many clusters?

* findings
