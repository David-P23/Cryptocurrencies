# Cryptocurrencies

## Overview
In this analysis I use unsupervised machine learning to analyze data directly  
from CryptoCompare, one of the largest providers of cryptocurrency market data.  
To form potential new investment products I group the different cryptos and  
analyze the different clustering results. PCA and K-Means clustering were used  
to prepare the data. Clusters were predicted by K-means algorithms after the  
less less meaningful dimensions were removed by component analysis. 
  
This is visualized by the output below.

## Results
Dataset:  
![image](https://user-images.githubusercontent.com/91306342/156950019-45d69ea0-ec8a-4ff7-aeeb-d0c6415086f7.png)  

***K-Means Algorithm***  
![image](https://user-images.githubusercontent.com/91306342/156950318-01a426ae-cced-4fdd-b0cb-9e491519844e.png)  
This indicates that the data is best sorted in to 4 categories/clusters.  

## Visualizing Cryptocurrencies Results

***3D Scatter plot using Plotly Express:***  
![image](https://user-images.githubusercontent.com/91306342/156950519-25d8d213-0116-48f1-9ab7-b1164432756a.png)  
Visualization of the crypto data is shown using three key metrics.

***Tradeable Cryptos Table***
![image](https://user-images.githubusercontent.com/91306342/156951158-ecaea676-49bc-4bd7-8d37-eab064e6c36c.png)
The hvplot function used to display the ***532*** tradeable cryptos in the data.

***2D Scatter Plot- TotalCoinMined & TotalCoinSupply***
![image](https://user-images.githubusercontent.com/91306342/156951476-fe24ecf3-d2b9-4efd-8d52-74775e58eb6f.png)
Indicates less than 3 dimensions does not allow meaningful analysis of the data.

## Summary  
Using the above methods it was determined the data should be grouped in to four  
classes. These classes were visualized usind diffreent methods for further  
explotarion. This info definitely gives the financial products company direction  
despite them having no expertise in cryptocurrency as they integrate crypto in  
to their financial products.
![image](https://user-images.githubusercontent.com/91306342/156952541-2fe2f071-73fe-424f-be3c-5bc1e892cedd.png)
