# Cryptocurrencies
## Overview of Analysis
Using unsupervised machine learning create an analysis of the cryptocurrency market with data from CryptoCompare (https://min-api.cryptocompare.com/data/all/coinlist)
Data needed to be processed clustered. Using principle componet analysis (PCA) to reduce the priniciple componets. K means was used for additional analysis. There are 4 deliverables in this module. screenshots will be used to highlight the outcomes of each deliverable section. 
## Resources
This module used: Python with: Pandas, Hvplot, Plotly, and Sklearn. Within Sklearn StandardScaler, MinMaxScaler, PCA and K means were imported. Jupyter notebooks running on the mlenv kernel was the main technology used to code. 
## Results

### Deliverable 1
The object of deliverable 1 was to create a cleaned dataframe for further analysis. That data frame can be seen in the image below:

![image](https://user-images.githubusercontent.com/90878901/151667889-76f64e0c-edf7-47dd-9b27-a78feff7189b.png)

During the execution of deliverable 1, the course asked for all of the algorithms that were working to be kept. For the analysis addional steps were added to ensure non working algorithms were identified. 

### Deliverable 2
Deliverable 2s objective was to use PCA and create 3 principle componets. These 23 can be seen in the next image: 

![image](https://user-images.githubusercontent.com/90878901/151668025-4ffc7e58-00a4-447c-ad30-c8bc9bc4d591.png)

### Deliverable 3
Deliverable 3 was to cluster the crypto currencies using K-means
An Elbow curve was created to identifiy the number of clusters as seen below: 

![image](https://user-images.githubusercontent.com/90878901/151668124-53e053ef-623b-4437-adcf-1a0a7a24a9ad.png)

A table was then created to include the  "predicted clusters and crypocurrencies features"

![image](https://user-images.githubusercontent.com/90878901/151668177-28cf7b22-637b-4f26-bf77-efd650d5e421.png)

### Deliverable 4
Deliverable 4 summarizes the data into a 3_d Scatter plot create a new table with the clustered data and create a fina scatter plot. 

Here is the 3-D scatter plot showing the clusters and adding the coin name feature. 

![image](https://user-images.githubusercontent.com/90878901/151668286-088f6a3a-00be-411e-aa45-3a7aa820b45a.png)

Below is the requested new data table.

![image](https://user-images.githubusercontent.com/90878901/151668317-98ec6945-2dc6-456b-a4e6-770793942e1d.png)

The classification is shown as well as the total supply and the total coins mined. 

Next is a summary table:

![image](https://user-images.githubusercontent.com/90878901/151668370-1897615b-c639-4f05-b753-2352524b2c64.png)

Finally the scatter plot also including the coin name field on hover. 

![image](https://user-images.githubusercontent.com/90878901/151668406-ae46f825-c4de-49ea-8b3d-d95b970e07ca.png)


## Summary
Unsupervised machine learning can be usefull when reviewing large and unknown datasets. The next steps for this analysis is to take the results and run supervised machine learning on those results to confirm more of the analysis and then create a set of recomendations for the audience for the data. 

