# SVD-on-Amazon-Food-reviews
Implementation of SVD on Amazon Food Reviews
SVD (Singular Value Decomposition):

•	Singular Value Decomposition (SVD) is a common dimensionality reduction technique in data science
Applications of SVD:
1.	Image Compression
2.	Image Recovery
3.	Eigenfaces
4.	Spectral Clustering
5.	Background Removal from Videos.
SVD: 
1.	SVD is a decomposition of matrix into three matrices into U,S and V.
2.	‘S’ is a singular matrix(Important values of different features).
3.	Rank of a matrix is a measure of unique information stored in matrix. Higher the rank more , more the information.
4.	Eigen vectors of a matrix are directions of maximum spread or variance of data.

Image Recovery:
Eg: The basic fact that helps to solve this problem is that most users have a pattern in the movies they watch and in the ratings they give to these movies. So, the ratings-matrix has little unique information. This means that a low-rank matrix would be able to provide a good enough approximation for the matrix.
This is what we achieve with the help of SVD.
Where else do you see this property? Yes, in matrices of images! Since an image is contiguous, the values of most pixels depend on the pixels around them. So a low-rank matrix can be a good approximation of these images.

Rank of a Matrix
The rank of a matrix is the maximum number of linearly independent row (or column) vectors in the matrix. A vector r is said to be linearly independent of vectors r1 and r2 if it cannot be expressed as a linear combination of r1 and r2.
 

This transformer performs linear dimensionality reduction by means of truncated singular value decomposition (SVD). Contrary to PCA, this estimator does not center the data before computing the singular value decomposition. This means it can work with scipy.sparse matrices efficiently
In particular, truncated SVD works on term count/tf-idf matrices as returned by the vectorizers in sklearn.feature_extraction.text. In that context, it is known as latent semantic analysis (LSA).

https://www.machinelearningplus.com/nlp/cosine-similarity/
 










