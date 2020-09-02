# Clustering-of-Countries
This assignment involved the problem statement where we need to cluster countries based on 3 important variables gdpp, income, and child mortality.<br />
The data we got had no nulls or NAs or in other words, was in no need of cleansing. But when trying to analyze the spread of data for each variable I got to know about the outliers it had. Worked with removing outliers which didn’t change the result significantly on the data I was working on. But if you are deleting entire outliers it would lead to losing 25% of the data. So, I left it as it is since clustering would take care of the outliers.<br />
<br />
After data was ready PCA was used to reduce dimensionality in the data and scree plot was used to find out the variability that each component would explain based on which I got to choose 5 principal components, which would explain variability in most of the data.<br />
## Clustering: Both k-means and Hierarchical clustering were used to see which would offer a better result.

For K-means with the help of the silhouette score and elbow curve, I selected 4 clusters. And Hierarchical clustering looking at Dendrogram helped me to identify clusters and it made sense to choose 4 clusters.
When looking at 2 types of clustering both seem to produce a similar result
