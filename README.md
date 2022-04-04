# Implementation of the t-SNE algorithm
Implementation of the following paper: https://www.jmlr.org/papers/volume9/vandermaaten08a/vandermaaten08a.pdf by Laurens van der Maaten and Geoffrey Hinton

### About t-SNE
t-SNE is a technique that visualizes high-dimensional data by giving each datapoint a location in a two or three-dimensional map. The technique is a variation of Stochastic Neighbor Embedding (Hinton and Roweis, 2002) that is much easier to optimize, and produces significantly better visualizations by reducing the tendency to crowd points together in the center of the map. t-SNE is better than existing techniques at creating a single map that reveals structure at many different scales. This is particularly important for high-dimensional data that lie on several different, but related, low-dimensional manifolds, such as images of objects from multiple classes seen from multiple viewpoints.
