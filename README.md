# KMeans-with-PCA
This notepad describes how to adopt the Principal component analysis on the clustering algorithm K-Means. 

The input file contains the different sales or import of wheat in the unit of tons to different countries from a single manufacturer. The units will be represented based on the consumption of wheat from the year 1990 to 2007. 

Based on the data captured identify the countries with a low consumption and also countries which has a continuous increase in the consumption rate.

Analysis done.

1. Load all the python libraries.

2. Basic cleansing of data(Handling null values)

3. Apply the principal component analysis.

4. Obtain the variance ratios and plot a graph for the same to identify the number of principal component analysis.

5. Fit the PCA model.

6. Fit the Kmeans model based on the data generated out of the PCA. You can indentify the number of clusteres to be created using the elbow curve method.

7. Merge the data with its PCA values and the cluster identifier, this helps to identify the countries which are clustered together based on the consumption.

8. Plot the clusters in a graph for better understanding.
