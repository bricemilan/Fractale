# Mandelbrot fractale
Simple code to compute the mandelbrot set using only numpy arrays 
1° we initialize a 2D plane with x,y coordinate (a 3rd dimension for the rgb dimension is not used), d is the picture definition
2° we initialize the running variable as Z=0 and the fractale as uniform 255 (number of colors) to be computed
3° the famous computation as Z=Z^2+plan (matrix form)
4° all the coordinates that diverge (distance to 0=nan) are stored as 1 is the fractale array
5° the code call the function and display it using matplotlib
