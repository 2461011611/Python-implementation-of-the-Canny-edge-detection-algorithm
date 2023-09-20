# Python-implementation-of-the-Canny-edge-detection-algorithm

Python implementation of the Canny edge detection algorithm The various steps of Canny Edge Detection algorithm:

1. Load the image.

2. Convert the image to grayscale.

3. Perform Gaussian smoothing: The image is smoothed using a 3x3 Gaussian kernel to minimize the effect of noise on edge detection.

4. Calculate gradient and gradient direction: by calculating the gradient at each pixel point in the image, along the x and y directions respectively.

5. Gradient Direction Discretization: Converts the gradient direction into discrete angular values, making subsequent processing easier.

6. Non-Maximum Suppression: Performs non-maximum suppression on the image, retaining the pixels with the largest local gradients and suppressing the others.

7. Dual Thresholding: divides the image into three regions: strong edges, weak edges and background.
  
8. Edge tracking:By tracking the weak edges and connecting them to the strong edges to get the complete edge line.
