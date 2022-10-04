# Image_Compression_Using-K-Means-And-PCA
The K-means clustering algorithm is implemented and applied to compress an image. In a second step, principal component analysis is used to find a low-dimensional representation of the same image. And then the result of both the algorithms was compared based on SSIM and the amount of variance preserved for a particular compression ratio.

Image compression was successfully performed.
Results were as below:
Using K-Means, with a compression ratio of 425.76 it was possible to
achieve SSIM (structural similarity index measure) of 93
percent(0.930384).
And while using PCA, with a compression ratio of 425.76 it was possible to
achieve SSIM (structural similarity index measure) of 81
percent(0.811).
Hence,K-Means is more recommended to be used in reducing image
size compared to PCA but if we want to keep the overall color of the
original image, we prefer PCA.
