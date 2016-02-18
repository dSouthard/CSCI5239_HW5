# CSCI5239_HW5
WebGL
Diana Southard
CSCI 5239 Spring 2016

#### Directions

Create a program that allows a scene to be viewed in 3D from any direction
under user control using WebGL.

At a minumum you need to add lighting and textures to Ex 8 and draw a different
3D solid object.

You may use Apple's CanvasMatrix library of functions provided in class or an
equivalent library to provide the transformation functions needed since I am
assuming that you know how to do transformations from the previous class.
However, you may NOT use libraries to create the objects.  The purpose of this
assignment is to give you some exposure to how objects are built in OpenGL ES.

You MAY NOT use the Three.js library or equivalent packages that does all the
OpenGL calls for you.  The reason is that it abstracts the objects and controls
to the extent that you never see WebGL.  I want you to see how WebGL actually
uses OpenGL ES 2.0.


#### Program Use Instructions
This program features a sphere textured with a map of the world.
* Use your mouse cursor to rotate the globe.
* Use the sliders below the globe to adjust the light's position
* Click on the checkbox to enable the earth to rotate on its own. Note: This disables any mouse events on the globe until the checkbox is unchecked.
* This program makes use of per-fragment lighting calculation and is based on the WebGL Lesson 15 at [Learning WebGL] (http://learningwebgl.com/blog/?p=1778) as well as example 8 from the course. It makes use of the glMatrix library for matrix calculations.


**Time To Complete Assignment:** ~8 hours
