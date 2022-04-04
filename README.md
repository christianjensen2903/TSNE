# Implementation of the t-SNE algorithm
Implementation of the following paper: https://www.jmlr.org/papers/volume9/vandermaaten08a/vandermaaten08a.pdf by Laurens van der Maaten and Geoffrey Hinton

### About t-SNE
t-SNE is a technique that visualizes high-dimensional data by giving each datapoint a location in a two or three-dimensional map. The technique is a variation of Stochastic Neighbor Embedding (Hinton and Roweis, 2002) that is much easier to optimize, and produces significantly better visualizations by reducing the tendency to crowd points together in the center of the map. t-SNE is better than existing techniques at creating a single map that reveals structure at many different scales. This is particularly important for high-dimensional data that lie on several different, but related, low-dimensional manifolds, such as images of objects from multiple classes seen from multiple viewpoints.


### Results
An example of what the algorithm is capable of is seperating the following multi-dimensional data (projected into 2d):
![Screenshot 2022-04-04 at 23 46 24](https://user-images.githubusercontent.com/15799390/161637758-d987ecd2-c296-4918-a95e-b2b5d4de847a.png)

Into:<br/>
![Screenshot 2022-04-04 at 23 46 33](https://user-images.githubusercontent.com/15799390/161637738-9e15463a-8a71-40c3-8fe3-d4d0c4e8bd7e.png)

