Create a program that generates images of the Mandelbrot set. The images are to be produced in the PPM format. The images may be colored in any manner desired, but should clearly be the Mandelbrot set. In addition your program must time the creation of the image and report average and standard deviations of these times.

The following components should be a generic (re-usable) as possible as they will be used in future assignments.

A means of timing an arbitrary function (use std::chrono)
The computation of averages and standard deviations
The computation of the colored of a pixel in a Mandelbrot image