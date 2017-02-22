###This is the submission of my first project for the Self-Driving Car Nanodegree.

The files of interest are:
1. P1.ipynb

2. WRITEUP.md

3. /writeup_output/


The code can be run directly from the IPython notebook, P1.ipynb.
The only items that may need to be changed are the hough = 1 and regression = 1. These turn on or off the overlays of each. 

All images for the write-up are contained in the writeup_output folder.

Thanks for giving me a new passion!

This project consisted of applying techiques learned in class to find lane line from dashcam video. The pipeline consisted of the following macro steps.

1. Grayscale or color mask image.

2. Gaussian smoothing.

3. Canny edge detection.

4. Lane region of interest masking.

5. Hough line detection.

6. Hough line averaging and lane annotation.
