## COLOR SLICING

HSV and HSL are descriptions of hue, saturation, and brightness/luminance, which are particularly useful for identifying contrast in images. These color spaces are frequently used in color selection tools in software and for web design.

In reality, color is a continuous phenomenon, meaning that there are an infinite number of colors. Color spaces, however, represent color through discrete structures (a fixed number of whole number integer values), which is acceptable since the human eye and perception are also limited. Color spaces are fully able to represent all the colors we are able to distinguish between.

Clownfish are easily identifiable by their bright orange color, so they’re a good candidate for segmentation. Let’s see how well we can find Nemo in an image.



## Python packages used:
* Matplotlib
* OpenCV
* Numpy
* Matplotlib

## Steps involved

*  Read image from opencv
*  Convert image to HSV format
*  Normalise the given image
*  Mask the image with original image using bitmasking



