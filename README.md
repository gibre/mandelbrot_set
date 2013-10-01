# Mandelbrot set generator

Draws a Mandelbrot set. The rendering is done with the SFML (version 2.1), here is the official site : http://www.sfml-dev.org/index.php.


Here are the controls :

Zoom in : z

Zoom out : s

Increase number of iterations : i

Decrease number of iterations : k

Move on the image : arrow keys

I advise you to not resize the window, at the beginning the maximum number of iterations is 60, so theres at most 60 loops done by pixel. It can be very long to compute if you increase the window's size and increase the maximum number of iterations. The computing is multi-threaded, but it still slow.

All the theory and base example was taken from there : http://lodev.org/cgtutor/juliamandelbrot.html . Go to this site it's awesome ! (http://lodev.org/cgtutor)
