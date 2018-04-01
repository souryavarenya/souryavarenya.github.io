---
layout:       project
date:         30 Nov 2017
title:        CAD in Manufacturing
caption:      Project for the course - CAD in Manufacturing
description:  >
  A variety of projects that help understand CAD in context of manufacturing
image:        /assets/img/project/cadim.png
screenshot:
  path:       /assets/img/project/cadim.png
  srcset:
    1920w:    /assets/img/project/cadim.png
    960w:     /assets/img/project/cadim.png
    480w:     /assets/img/project/cadim.png

---
This was probably the most interesting course in my seventh semester. With Prof. Sathyan Subbiah as the instructor, the classes and assignments were extremely engaging. All the assignments have been listed below with illustrations. Credits to my team-mate Jagannadh as well.

Majority of the coding assignments have been done on Jupyter notebook - Python and the repositories have been attached

### Assignment 2 - Wireframe Modeling of a Mouse

![design](mouse.jpg){:.lead}

The focus of this assignment was to get familiar with the structuring of CAD models. We were asked to develop our own data structure for storing and retrieving wireframe 3D models. This assignment was done on MATLAB and the code can be downloaded [here](Assignment2.zip). You can refer to the documentation in the report for understanding the way it is done.

### Assignment 3 - Geometrical Modeling, NURBS and B-Rep

This assignment covers multiple topics - Geometrical Modeling, NURBS and B-Rep structure.

a. Geometrical Modeling - We were asked to model the mouse on Fusion 360 using the sculpt feature and a reference mouse image.
![design](moused.png){:.lead}

b. NURBS - Understanding the recursive functions wasn't very easy, here's the implementation of NURBS.
![design](NURBS.png){:.lead}

c. B-Rep - Boundary Representation implemented in python. A sample shape was to be built and here it is.
![design](shape.png){:.lead}

[here's](Assignment3.rar) the submission!

### Assignment 5 - Feature Identification

With reference to the B-Rep structure developed in the last section of Assignment 3, this assignment was on detecting and highlighting a specific feature. Here, we were supposed to highlight triangular pockets.

![design](tripockte.png){:.lead}

Again, [here's](Assignment5.zip) the submission.

### Assignment 7 - Tool Path Planning

This assignment was about planning the tool path of a 5 axis CNC given the input of a bezier surface and tool parameters. The result is here, in the following video.

<div class="videowrapper">
  <iframe src="https://www.youtube.com/embed/cncuAMB9eMA?rel=0" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen> </iframe>
</div>

Code [here](Assignment7.zip)!

### Assignment 8 - 3D object slicing

The course concluded with this amazing assignment where we had to understand and import STL files and slice them for additive manufacturing.

![slice](slice.png)

Code [here](Assignment8.zip)!
