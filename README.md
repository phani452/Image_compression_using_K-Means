# Image_compression_using_K-Means
K-Means clustering is used to reduce the image to K number of the colours here K represents number of clusters. 
In K-Means clustering we will form the K number of clusters. we will find the centroid of the cluster which will be the resemblance of 
the colours present in the cluster.And we will replace each pixel value of the image with its respective cluster centroid. 
Hence the colour combination formed using K means clustering will far less than the actual colour combination of the image.
As the no of colours in the image is reduced the size of the image is also reduced and the image is compressed.
So the ordinary image contains the three channels (R, G, B) and each channel contains the values from (0 to 255) 
So the all possible combinations of (R, G, B) channel present in the image are 255*255*255=1,65,81,375 so total 
1,65,81,375 Combinations of colours are present. But human eye cannot notice the all colours. It can notice only some colours.
The visual perception of the human eye is taken as advantage by the K-Means clustering .it reduces the size of the image or compresses 
the image by reducing the number of the colours. Colours with different intensity values of (R, G, B) seems similar to human eye,
Hence K-Means clustering forms the clusters with the similar colours.so K-Means can club similar colors into a cluster and represent by 
a centroid point that almost has same resemblance to the human eye.
