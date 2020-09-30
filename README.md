# test-texify
On the computer, it is straightforward
[discretize](https://en.wikipedia.org/wiki/Discretization) an implicit
function. We define a regular 3D grid of
[voxels](http://en.wikipedia.org/wiki/Voxel) containing at least the [bounding
box](https://en.wikipedia.org/wiki/Minimum%5Fbounding%5Fbox) of <img src="/tex/7d2e1b8689e4bf3e2eb6c0bda84acf10.svg?invert_in_darkmode&sanitize=true" align=middle width=7.30598714999999pt height=22.831056599999986pt/>. At each
node in the grid <img src="/tex/5edfc658929905d36279f4a1383c1225.svg?invert_in_darkmode&sanitize=true" align=middle width=25.121916599999988pt height=14.15524440000002pt/> we store the value of the implicit function
<img src="/tex/837c927519e915f57c13321c58aa67ad.svg?invert_in_darkmode&sanitize=true" align=middle width=47.159554199999995pt height=24.65753399999998pt/>. This defines <img src="/tex/3cf4fbd05970446973fc3d9fa3fe3c41.svg?invert_in_darkmode&sanitize=true" align=middle width=8.430376349999989pt height=14.15524440000002pt/> _everywhere_ in the grid via [trilinear
interpolation](https://en.wikipedia.org/wiki/Trilinear_interpolation).
