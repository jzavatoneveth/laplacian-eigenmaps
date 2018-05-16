# laplacian-eigenmaps
Spectral embedding using Laplacian Eigenmaps

## Getting Started
The `laplacianEigenmapsDemo` script demonstrates basic usage of the core `laplacianEigenmaps` function for several classic manifold learning examples.

## Prerequisites

This code was tested in MATLAB R2017b.
As the [`graph`](https://www.mathworks.com/help/matlab/ref/graph.html) and [`conncomp`](https://www.mathworks.com/help/matlab/ref/graph.conncomp.html) functions were first introduced in R2015b, that is likely the oldest version of MATLAB in which this code will run.
The syntax for optional inputs to [`eigs`](https://www.mathworks.com/help/matlab/ref/eigs.html) changed in R2017b, hence that function call will likely need to be modified for use in earlier versions of MATLAB.
No dependencies outside of the MATLAB standard library are required.

## References:

1. Belkin, Mikhail, and Partha Niyogi. "Laplacian eigenmaps for dimensionality reduction and data representation." _Neural Computation_ 15.6 (2003): 1373-1396. [(Link)](https://ieeexplore.ieee.org/document/6789755/)

2. Bengio, Yoshua, et al. "Learning eigenfunctions links spectral embedding and kernel PCA." _Learning_ 16.10 (2006). [(Link)](https://www.mitpressjournals.org/doi/abs/10.1162/0899766041732396)

3. Ng, Andrew Y., Michael I. Jordan, and Yair Weiss. "On spectral clustering: Analysis and an algorithm." _Advances in Neural Information Processing Systems_ (2002). [(Link)](https://papers.nips.cc/paper/2092-on-spectral-clustering-analysis-and-an-algorithm.pdf)

4. van der Maaten, Laurens, Eric Postma, and Jaap van den Herik. "Dimensionality reduction: a comparative review." _Journal of Machine Learning Research_ 10 (2009): 66-71. [(Link)](https://lvdmaaten.github.io/publications/papers/TR_Dimensionality_Reduction_Review_2009.pdf)

## License

This project is licensed under the [MIT License](LICENSE.txt).
