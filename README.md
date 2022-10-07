# Image Compression using KMeans

The K-means algorithm can be used to compress the image. Unlike lossless compression, K-means uses lossy compression, so it is not possible to recover the original image from the compressed image. The larger the compression ratio, the larger the difference between the compressed image and the original image. The principle of K-means clustering algorithm for compressing images is as follow:

- Preferred number of selected clusters 𝐾 is very import, 𝐾 must be less than the number of image pixels 𝑁
- Using each pixel of the image as a data point, clustering it with the K-means algorithm to obtain the centroid 𝝁
- Storing the centroid and the index of the centroid of each pixel, so it not need to keep all the original data

## Results
![Kmeans Results](https://github.com/SajjadPSavoji/Image-Compression-Kmeans/blob/master/KmeansBanner.jpeg)

## Resources
 - [Lossy and Lossless Image Compression](https://www.techtarget.com/whatis/definition/lossless-and-lossy-compression)
 - [KMeans for Image Compression](https://iq.opengenus.org/image-compression-using-k-means/)
 - [Kmeans Explained](https://neptune.ai/blog/k-means-clustering)
 - [Kmeans using Sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)
