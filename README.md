SVD [Singular value decomposition]

In linear algebra, the singular value decomposition (SVD) is a factorization of a real or complex matrix, with many useful applications in signal processing and statistics.
Formally, the singular value decomposition of an m×n real or complex matrix M is a factorization of the form
M = UΣV*

where U is a m×m real or complex unitary matrix, Σ is an m×n rectangular diagonal matrix with nonnegative real numbers on the diagonal, and V* (the conjugate transpose of V, or simply the transpose of V if V is real) is an n×n real or complex unitary matrix. The diagonal entries Σi,i of Σ are known as the singular values of M. The m columns of U and the n columns of V are called the left-singular vectors and right-singular vectors of M, respectively.
The singular value decomposition and the eigendecomposition are closely related. Namely:
The left-singular vectors of M are eigenvectors of MM*.
The right-singular vectors of M are eigenvectors of M*M.
The non-zero singular values of M (found on the diagonal entries of Σ) are the square roots of the non-zero eigenvalues of both M*M and MM*.
Applications which employ the SVD include computing the pseudoinverse, least squares fitting of data, matrix approximation, and determining the rank, range and null space of a matrix.
