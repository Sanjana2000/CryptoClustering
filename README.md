# CryptoClustering

First, I imported the required libraries and dependencies and read the csv data into a Pandas DataFrame. I generated the summary statistics using describe. I plotted the data to see the visual interpretation of the DataFrame.

Next, I scaled the data using Standard Scaler. Using this new data, I created a scaled DataFrame.

I found the best value for K using the data by looping through it and appending it to an inertia list. Using an elbow curve graph, I identified the best value for k as 4. 

Using the K-Means model, I made predictions with the data and plotted the clusters.

Next, I used PCA with 3 principle components to fit the data. The amount of variance that was explained by the components was found using explained_variance_ratio and multiplying by 100.

I created a new DataFrame using the PCA data and found the best K value using the same looping technique as before. The new elbow curve revealed the optimal value for K as 4, the same as prior. 

Plotting these clusters showed a very different visual graph as the earlier graph. Both can be shown in the comparison code at the end. 
