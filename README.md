# Cryptocurrencies

## Overview
The data Martha will be working with is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what Martha is looking for, she has decided to use unsupervised learning. To group the cryptocurrencies, Martha decided on a clustering algorithm. She’ll use data visualizations to share her findings with the board.

## This new assignment consists of four technical analysis deliverables. You will submit the following:
- Deliverable 1: Preprocessing the Data for PCA
- Deliverable 2: Reducing Data Dimensions Using PCA
- Deliverable 3: Clustering Cryptocurrencies Using K-means
- Deliverable 4: Visualizing Cryptocurrencies Results

## Results
### Out of an original 1,252 entries, we narrowed down to 1,144 cryptocurrencies currently being traded.  Null values were also removed, as well as cryptocurrencies that had a total number of mined coines greater then 0.  This scaled our dataset down to 532 tota tradable cryptocurrencies.
<img width="600" alt="1  currently trading" src="https://user-images.githubusercontent.com/104927745/195659409-e1829d9c-a61c-4ace-9333-a6519c589e85.PNG">

### In utilizing the Elbow Curve method, a slope of 4 was the result, which was the number of clusters in the kmeans alogrithm.
<img width="600" alt="2  elbow curve" src="https://user-images.githubusercontent.com/104927745/195659418-09a2c9c8-30d7-4353-b964-5bb23203fb9e.PNG">

### These clusters were then plotted in a 3D scatter plot to further visualize the data.
<img width="600" alt="3  scatter plot" src="https://user-images.githubusercontent.com/104927745/195659796-fa4c3474-461f-4e32-8e02-83909c654839.PNG">

## Resources
- Jupyter Notebook, Python, Anaconda, provided CSV file (crypto_data.csv), Crypto Clustering Starter code (.ipynb)
