# FdF
## About

FdF is a project in which we convert a file with a grid of height values into a 3d wireframe using a simple graphics library called MiniLibX.

It is possible to rotate and translate(move) de grid.
Also it is possible to move and rotate the view perspective.

## Installation

The program can be build with a simple `make all`
You do need to have the X11 server and X11 library, where the minilibx library is based upon.

## Examples

### Simple example of functionality
The following is an example of a .fdf file we use as an input for our program:
```
0 0 1 2 3 4 5 6 7 8 9
0 0 0 1 2 3 4 5 6 7 8
0 0 0 0 1 2 3 4 5 6 7
0 0 0 0 0 1 2 3 4 5 6
0 0 0 0 0 0 1 2 3 4 5
0 0 0 0 0 0 0 1 2 3 4
0 0 0 0 0 0 0 0 1 2 3
0 0 0 0 0 0 0 0 0 1 2
0 0 0 0 0 0 0 0 0 0 1
```
which produces the following:
![Screenshot from 2024-08-22 09-42-38](https://github.com/user-attachments/assets/9246d1ad-4aab-44b5-b994-3d2e85c16bab)

### simple grid
picture coming

### Example of rotation, translation, zoom, flattening and perspective changes(coming)
picture coming

### Example of map with custom colors

<img width="1236" alt="Screen Shot 2022-09-15 at 2 34 42 PM" src="https://user-images.githubusercontent.com/21006147/190404961-988cedf9-bed6-417f-bed3-eb5dc2b7afda.png">

### Example with large map
<img width="1910" alt="Screen Shot 2022-09-15 at 2 38 15 PM" src="https://user-images.githubusercontent.com/21006147/190406149-d0d13cb6-c3eb-4594-abf8-d22c5b005485.png">
