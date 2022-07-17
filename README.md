Cryptocurrencies

## Analysis Overview

- Preprocessing the Data for PCA
- Reducing Data Dimensions Using PCA
- Clustering Cryptocurrencies Using K-means
- visualizing classification results with 2D and 3D scatter plots.

### Purpose 
Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked you to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.
<br><br>

## Resources
**Data Source: ** [crypto_data.csv] 

(https://github.com/erickzcu4975/Cryptocurrencies/blob/main/Resources/crypto_data.csv).

**Software:** Python, Conda, Jupyter Notebook.


## Results


### Clustering Cryptocurrencies using K-Means - Elbow Curve
The result/output of this analysis is unknown so unsupervised machine learning is utilized to identify clusters for cryptocurrencies.\
The K-Means method iterating on k values from 1 to 10. 

The best k value appears to be 4 so in conclusion to use an output of 4 clusters to categorize the crytocurrencies.
<br><br>

### Visualizing Cryptocurrencies
#### 3D-Scatter plot with clusters

The 3-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components.
<br><br>

#### 2D-Scatter plot with clusters

The 2-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to two principal components.
<br><br>
Both scatter plots show the distribution and the four clusters of cryptocurrencies.<br>
The outliers identify the unique cryptocurrency in the class #2.
<br><br>


#### 2D-Scatter plot with TotalCoinMined vs TotalCoinSupply

Scatter plots frm two cryptocurrency features arent efficiently segregated by classes. Using the PCA algorithm is the right method for visualizations.
<br><br>

## Summary
The classification of 532 cryptocurrencies is based on similarities among features.
Each group need to be analyzed to determine performance and interest for the investment bank's clients.

