
Rik Verhoeven
Fil De Fer(FDF) project 42 School


Fil De Fer means Wireframe in English, this what the project 
is all about.

The goal is to parse a given 2d map and transform this into a 3d perspective.
The mandatory part of the project is to render one isometric projection,
but you can be as creative as you want such as adding transformations.
Examples of transformations are: Rotation, Shearing(stretching), Scaling.
This project is also able to zoom in, out and move in all directions.

Calculations are done with Matrix multiplication.



Compiling:
This project makes use of the MLX42 library.
The MLX42 library makes use of glfw3 and OpenGL


Usage:
run in the terminal;
./fdf maps/test_maps/(any map you like)
Rotate Model
Q	+Around Y
W   +Around Z
E   -Around Y
A   -Around X
S   -Around Z
D   +Around X
Rotate view
I	Over
K   Backwards
J   leftwards
L   rightwards
Zoom
+ 
-
Moving
left 
right
down 
up    




Resources:

subject explain
https://m4nnb3ll.medium.com/fil-de-fer-fdf-the-first-graphical-project-at-42-the-network-5cce69203448

graphics general
https://www.scratchapixel.com/lessons/3d-basic-rendering/introduction-to-ray-tracing/how-does-it-work.html

isometric
https://en.wikipedia.org/wiki/Isometric_projection


3D transformations
https://www.youtube.com/watch?v=rHLEWRxRGiM


bresenham line algo
https://digitalbunker.dev/bresenhams-line-algorithm/


interpolate
https://www.youtube.com/watch?v=Xj129kA3Ci0
https://michael-m.medium.com/true-color-interpolation-a1a17352ebf0
https://www.alanzucconi.com/2016/01/06/colour-interpolation/
