# unsupervised_learning_challenge
In this project I use unsupervised machine learning algorithms to classify the subjects with different features collected to study myopia. 
<br>

First I created the feature-only dataframe by removing the target class. The feature number was reduced by using principal component analysis (PCA). I also used TSNE model to further reduce the features obtained after using PCA. 

<br>

The elbow curve was then plotted to estimate best number of classes from for the features.
<br>
![Elbow_curve](https://user-images.githubusercontent.com/99154332/184155863-15e9bd15-206e-4cdb-998f-e0db7d65a2e5.png)

<br>

The K-means clustering algorithm was then applied with the tsne data and number of clusters as 3, as indicated by the elbow curve. The clustering plot indicates a clear indication of 3 clusters as shown in picture below. 
<br>

![tsne_clusters](https://user-images.githubusercontent.com/99154332/184156765-70309e78-14d9-47df-965a-83fe06ecc6af.png)
