Environment: Weka

The dataset is taken from:
"Molecular Classification of Cancer: Class Discovery and Class Prediction by Gene Expression Monitoring"1, T. R. Golub et al., Science, Volume 286, 1999I. Clustering without PCA:Ran two clustering algorithms → k-means and hierarchical clustering with k=2 and k=3 both. Weka also has a seed parameter for clustering. I changed that to obtain best clustering results.

II. Clustering after PCA: 
Run the clustering in Step I again after PCA

III. Classification 
Used Weka to build a classification model of the training data.Also, built the model using four different algorithms (preferably ensemble methods).