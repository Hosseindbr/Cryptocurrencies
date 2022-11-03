# Cryptocurrencies
Using unsupervised machine learning to to get into the cryptocurrency market.

![original_imagesoriginal_imageshttpsg foolcdn c width-880_SfbkM9V](https://user-images.githubusercontent.com/108313440/199642495-0e591033-d0bf-48fe-8230-af226d7e4414.jpg)


## Overview of the Project

An unsupervised machine learning algorithm is used in this project to analyze a database of cryptocurrencies and to categorize them based on their characteristics.Investing banks could use this classification report to present their clients with a cryptocurrency investment portfolio. The following steps were taken to analyze the database:

- preprocessing the database

- reducing the data dimension using Principal Component Analysis

- clustering cryptocurrencies using K-Means

- visualizing classification results with 2D and 3D scatter plots 



## Resources

- crypto_data.csv Dataset 

- Software: Python 3.7.9, Anaconda 4.9.2 and Jupyter Notebooks 6.1.4

- Libraries: Scikit-learn, Plotly, hvPlot, Pandas

## Results

After the data cleaning, the number of tradable cryptocurrencies reduced from 1252 to 532.

<img width="745" alt="Screenshot 2022-11-03 at 12 34 04 AM" src="https://user-images.githubusercontent.com/108313440/199648244-b7892ccc-72ad-499b-a4d7-63bea4e6aee4.png">


### Clustering Cryptocurrencies using K-Means - Elbow Curve

This elbow curve was produced by iterating on k values between 1 and 10 using the K-Means method. On the basis of the bellow curve, four clusters are considered optimal (k=4).

<img width="702" alt="Screenshot 2022-11-03 at 12 01 18 AM" src="https://user-images.githubusercontent.com/108313440/199647716-dcbe10bd-7c7d-4bc4-b151-c3122baa1676.png">


### 3D Scatterplot with Clusters

Based on the PCA, a 3D scatter plot was created showing where each clustered crypto was located in relation to the 3 principal components. The data shows that there are three main groups and one outlier.

<img width="800" alt="Screenshot 2022-11-03 at 12 01 31 AM" src="https://user-images.githubusercontent.com/108313440/199647772-390f3232-1e19-4767-8926-cd2ed66e4d52.png">


### 2D-Scatter plot with TotalCoinMined vs TotalCoinSupply
Two outliers can be seen when graphing clustered cryptos by terms of total supply and total mined coins. The first one has a big supply and a lot of mined coins, while the second one has a big supply but not many mined coins (TurtleCoin).


<img width="665" alt="Screenshot 2022-11-03 at 12 02 10 AM" src="https://user-images.githubusercontent.com/108313440/199647818-9269c6fc-3f13-4583-bf52-c9dc483dd34a.png">





