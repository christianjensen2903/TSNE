# Implementation of the t-SNE algorithm
Implementation of the following paper: https://www.jmlr.org/papers/volume9/vandermaaten08a/vandermaaten08a.pdf by Laurens van der Maaten and Geoffrey Hinton

### About t-SNE
t-SNE is a technique that visualizes high-dimensional data by giving each datapoint a location in a two or three-dimensional map. The technique is a variation of Stochastic Neighbor Embedding (Hinton and Roweis, 2002) that is much easier to optimize, and produces significantly better visualizations by reducing the tendency to crowd points together in the center of the map. t-SNE is better than existing techniques at creating a single map that reveals structure at many different scales. This is particularly important for high-dimensional data that lie on several different, but related, low-dimensional manifolds, such as images of objects from multiple classes seen from multiple viewpoints.


### Results
An example of what the algorithm is capable of is projecting the following 3D data:<br>
![3d](https://user-images.githubusercontent.com/15799390/196543426-5841fcf6-0fce-4b54-ad2c-1e69068ef1a8.png)


Into:<br/>
![good](https://user-images.githubusercontent.com/15799390/196543535-5b75b172-b599-4a7c-86ad-6c5fc9a24ce7.png)

If PCA was to be used instead one would get the following result: <br>
![pca](https://user-images.githubusercontent.com/15799390/196544038-c273ebb5-f41c-4775-aed5-d8633199e3e8.png)

It is clear the t-SNE sometimes clearly is better at representing the data in a lower dimensionality than PCA.


