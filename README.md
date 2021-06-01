# Image Segmentation on Kitchen utensils images
This notebook shows connected component labelling to segment objects from an image.

## Language
Python is used along with OpenCV to carry-out all computer vision functions.

## Approach Steps
Following are the steps followed to segment object from images:
1. First the image is blurred using 5x5 Gaussian Filter
2. Image is resized into a smaller resolution
3. RGB image is converted into Grayscale image
4. Histogram Equilizer is applied on the gray image
5. image is binarized using binary threshold function
6. Connected components are computed with connectivity parameter set to 8
7. Very small objects are removed using area condition on each component
8. Our required object is usually have a fix height over width ratio. By threshold on each component we get thre required object.

## Results
Following are the results of image segmentor:

Plate

