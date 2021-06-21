# Cryptocurrencies

## Overview

Using Unsupervised Machine Learning we will attempt to use a cryptocurrency dataset that are on the trading market, group them to create some sort of classification on how to strategize this relatively new market for sound investment. Unsupervised Learning Machine algorithms are designs from a dataset without any known features or target that we use to determine trends or grouping. Transformation and Clustering are two aspects of unsupervised learning that will be in this module challenge. First will try to transform the dataset then use 3D scatter plot or scatter plot to see how well data or values are group together. These visualizations may help to trends of grouping and make an informed decision about this new market.  

## Results

The crypto_clustering.ipynb file will try show the process how the raw dataset was manipulated using python, to produce the categories shown for different classes of the 2D and 3D scatter plot visualizations. As usual, for the dataset to be analyzed, it must be cleaned and formatted into columns values that are understood by the different functions, algorithms and the computer. Some of the process that were involved are as follows:
-	Dropping of null values 
-	Getting rid columns that we might interpret to have no value on the outcome.
-	Changing values to readable data for the computer to manipulate
-	Using transformation algorithms
-	Function to determine the number of clusters to be used.
-	Creating new dataframes 
-	Showing visualizations 
 
## Summary
K-means algorithm produce the elbow curve that is used to determine the number clusters for the analysis. 3D scatter plot shows a much clearer distinction of the four (4) groups than the 2D scatter plot. Two groups in the 3D plot, class 1 and 2 clusters are organized around a center point or centroid, class 3 scattered and could produce more than one grouping and class 4 which is a single point, seems more of an outlier in the dataset. Instructions from the challenge 4 we were required to use K-Means with K=4 but, a more accurate grouping of K=5 seems to be the case with a closer look at the elbow curve in step 3 of deliverables 1. The cryptocurrencies are classified in respect to the number of coins that are mined and the amount that is supplied, this comparison is a reflection of the value of the bitcoin and from this result a determination can be made on how make proper investment choice.
