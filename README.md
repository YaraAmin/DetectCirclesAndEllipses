Installation: python3-opencv-numpy-imutils

# SATURATION METHODS
## using opencv 
Convert BGR to HSV
Multiple hsv by a saturation_param to change the saturation

## using PIL
enhancement image saturation using ImageEnhance.Contrast by 3 different paramters -1, 2, 3



# Circle and Ellipses Detection Methods

## using opencv

### Blob Detection
I tried using Blob detection with changing the paramters of Inertia Ratio so it select also the ellipses not only the circles but it doesn't work very well for ellipses, only selected the circle.

### Hough Lines Transform
I used hough lines transform to select the straigh lines on the polygons shapes and neglect the circles ans ellipses and it worked very weel with the suitable paramters.

## Approximation
The Best results for detecting circles and ellipses.
First i filtered the shapes from any shapes don't contain any curves
Second based on lenght of approximations of each lefted shape i managed to detect only circles and ellipses

