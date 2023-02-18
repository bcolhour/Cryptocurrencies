# Cryptocurrencies
### Crypto analysis using unsupervised machine learning and Python

## Overview
Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers.The multitude of available cryptcurrencies can be overwhelming. The better known ones are beginning to price out the common buyer. 

We have been tasked to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

## Resources
  - Datasets: [crypto_data.csv ](https://github.com/bcolhour/Cryptocurrencies/blob/main/Starter_Code/crypto_data.csv)
  - Technologies used: 
    -  Python
    - Jupyter notebook
    - Sklearn, pandas, and hvplot libraries
    - Unsupervised Machine Learning

## Results
Importing the dataset: 

![image](https://user-images.githubusercontent.com/114044192/219822931-234831c2-1362-48da-b336-64ee9ae7c427.png)

Manipulate data to include tradable currencies without Null values
  - Fit the data (including converting string data to values)
  - Standardize data
  - Reduce Data Dimensions Using PCA
  - Create an Elbow Curve to determine best value for k
  
![image](https://user-images.githubusercontent.com/114044192/219822855-c8d1e700-5afd-41b0-903e-4d1ee6a6a909.png)

Run K-Means with k=4
  - Create new usable DF with all data

![image](https://user-images.githubusercontent.com/114044192/219823194-16f04293-2a3f-44a3-a334-838bd0a6c6f9.png)

### Create Visualizations
#### 3D Scatter with Clusters
![image](https://user-images.githubusercontent.com/114044192/219823294-5c53da5c-c9d8-484f-a9cf-798d7b11f929.png)


#### Table of tradable cryptocurrencies
![image](https://user-images.githubusercontent.com/114044192/219823348-728d8664-e4a8-4ce8-b947-4ee94779e5ae.png)

#### ScatterPlot
![image](https://user-images.githubusercontent.com/114044192/219823408-b2c22495-9407-44a4-9734-5676aaddcdfe.png)




