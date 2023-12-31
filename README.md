# 3DRender
A simple 3D object render engine in Java


First, use orthographtic projection to draw the frame of the shape.

orthographic projection - representing a 3D object by disregarding a dimension and casting it onto a 2D plane

![orthographic projection demo](Ortho-Projection.png)

The projectors are parallel lines that run perpendicular to the plane of projection

<img width="661" alt="Parallel-Projection" src="https://github.com/oZep/3DRender/assets/97713154/17c71699-4fc1-409b-ac3a-a6e1f85ab23d">

We rotate the object using these matrix transformations, any rotation in 3d can be represented by rotations of YX, ZY, and ZX




thanks to [this tutorial](http://blog.rogach.org/2015/08/how-to-create-your-own-simple-3d-render.html) for setting up the base pipeline + helping me understand basic 3D rendering at a low level
