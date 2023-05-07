# CryptoClustering 

--NOTE--

Analysis redone with k=4, rather than k=3
New file is "Crypto_Clustering_Andaya02.ipynb"

This analysis looks at various cryptocurrencies (41 total) and the effect of price changes on each for specific spans of time (24-hour vs 7-day).  The original data was scaled using StandardScaler module from the Scikit-learn library in Python.  Two K-means models were constructed using the original scaled data and principal component analysis of the scaled data.  The data was fit to each model and conclusions comparing the models and their clustering were made within the attached code (Crypto_Clustering_Andaya.ipynb).
