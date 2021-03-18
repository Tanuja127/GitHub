# Python Project: Multiple Colour Detection in Real-Time using Pandas and OpenCV

# About the Python Project:
In this colour detection Python project, we are going to build an application through which you can automatically detect the colour (Red , Blue and Green) in a livestream video content. 
We will use three main modules for this project. They are NumPy, Pandas and OpenCV. OpenCV is a highly optimized library with a focus on real-time applications.

# Accuracy: 
We can see that our model has an accuracy of 99.7% to detect the colours.

# Applications:
1) In self-driving car, to detect the traffic signals.
2) Multiple colour detection is used in some industrial robots, to performing pick-and-place task in separating different coloured objects.

# Python Libraries Used:
[1) NumPy](https://en.wikipedia.org/wiki/NumPy)

[2) OpenCV](https://en.wikipedia.org/wiki/OpenCV)

# Steps for building Python Code:
1. Capturing video through webcam
2. Reading the video from the webcam in image frames
3. Convert the imageFrame in BGR (RGB colour space) to HSV (hue-saturation-value) colour space
4. Set range for red, blue and green colour and define mask
5. Morphological Transform: Dilation, to remove noises from the images
6. Morphological Transform, Dilation for each colour and bitwise_and operator between imageFrame and mask determines to detect only that particular colour
7. Creating colour contour to track red, blue and green colour

# Code:
[Click here to view the code](https://github.com/Tanuja127/GitHub/commit/19fec9c80db7f1dccc66dfb4aa2156b79ba4ed81)
