Low-rank Subset is the following problem. Given a set of N vectors in finite-dimensional Euclidean space and integer k and n, choose n vectors, such that they are best approximated by k vectors. The error is either the sum of squares of residues or the sum of squares of residues normalized by the sum of squares of norms. Putting the n chosen vectors in matrix A, the error becomes the Frobenius norm of the difference between A and A_k, the best k-rank approximation of A (which can be computed via the SVD).

Dense low-rank subgraph is the following problem. Given a graph of N nodes, such that each node is associated with a vector in finite-dimensional Euclidean space and integer k and n, choose n nodes, such that they are well approximated by k vectors AND the subgraph induced by them is dense.

This repo is an exploration of this problem. main.tex is the write-up with the precise problem statement, a brief refresher on Singular Value Decomposition, and a few possible algorithms for this problem. The write-up is a rough draft, and goes hand in hand with the LowRank repo at https://github.com/Vilin97/LowRank.jl, which contains implementations of the algorithms described in the write-up.

This research was done in Summer, 2020 with Evimaria Terzi, a professor of Computer Science at BU. She supported me with a grant.
