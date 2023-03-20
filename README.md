# NLP_match_cv_job
Matching job titles to the CV texts


This was a short, first attempt, at working with a simple NLP project.
The purpose was to match job titles with resume texts. 

Adding to the complexity was the uploading of data from differnt file-types and directing them into similar data structures.

In addition to the matching a word clustering analysis was carried out.
Using K-mean clustering relevant keyword clusters were determind. 
Word clusting was found for the the resume_df and later for the positions_df. 
The positions_df was a significantly larger dataset and therefor the clustering seemed more logical. 
Additional meterics are necessary to determine that accuracy of these results. 
Since K-means clustering is unsupervised and therefore has no explicit lables or targets other evaluation metrics must be used.
One such method is silhouette score.

