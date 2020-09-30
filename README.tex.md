# test-texify
On the computer, it is straightforward
[discretize](https://en.wikipedia.org/wiki/Discretization) an implicit
function. We define a regular 3D grid of
[voxels](http://en.wikipedia.org/wiki/Voxel) containing at least the [bounding
box](https://en.wikipedia.org/wiki/Minimum%5Fbounding%5Fbox) of $\S$. At each
node in the grid $\x_{i,j,k}$ we store the value of the implicit function
$g(\x_{i,j,k})$. This defines $g$ _everywhere_ in the grid via [trilinear
interpolation](https://en.wikipedia.org/wiki/Trilinear_interpolation).
