# Background-Subtraction
Image Processing project of Background Subtraction using MATLAB

Approach used:
The objective of our project is to detect distinct objects from an image. Our code
should be capable of distinguishing between various objects and the background on
which all objects are laid upon.
We would be requiring 2 images for this purpose- one the actual background image
and the other with objects upon it. So we will input these two images. The size of
both the images should be same for proper functioning of operations as images are
represented as matrices in matlab.
Basically, we will iterate both our input images and track changes. For the image
with objects, we will detect large connected pixels with values different from
neighbors, label them with unique values, trace their boundaries and count them.
We will again iterate the image with objects and will show only the labeled pixels.
These would represent objects roughly.
We used the following set of techniques in order to implement the proposed idea:
· Acquisition of image
· Median Filtering
· Labelling
. Plotting
We’ll be using MATLAB to implement these techniques and hence achieving the
results.
