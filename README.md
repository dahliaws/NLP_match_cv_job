# NLP_match_cv_job
Matching job titles to the CV texts


This was a short, first attempt, at working with a simple NLP project.
The purpose was to match job titles with resume texts. 

Adding to the complexity was the uploading of data from differnt file-types and directing them into similar data structures.

Also, using K-mean clustering relevant keyword clusters were determined for the CVs and for the job descriptions.  
The positions_df was a significantly larger dataset and therefor more ideal for analysis. 

Since K-means clustering is unsupervised and therefore has no explicit lables or targets other evaluation metrics must be used.
Methods for validation used in this project were:
1. Silhouette score - A measure of how similar an object is to its own cluster compared to other clusters.
2. Calinski Harabasz Index - The ratio of the sum between-clusters dispersion and within-custer dispersion (or variance) for all clusters.
3. Davies Bouldin Index - The average similarity between clusters

