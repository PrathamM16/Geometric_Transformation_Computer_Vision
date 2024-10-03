# Image Transformation Project

This project demonstrates various image transformation techniques using OpenCV and Python. The code performs operations such as scaling, translation, rotation, flipping, affine transformation, and perspective transformation on an input image.

## Table of Contents
- [Overview](#overview)
- [Requirements](#requirements)
- [Image Transformations](#image-transformations)
- [Usage](#usage)
- [Output](#output)
- [References](#references)

## Overview
The project performs the following image transformations:
1. **Scaling**: Resizes the image to 50% of its original size.
2. **Translation**: Moves the image 100 pixels to the right and 50 pixels down.
3. **Rotation**: Rotates the image by 90 degrees in a clockwise direction.
4. **Flipping**: Horizontally flips the image (mirror effect).
5. **Affine Transformation**: Warps the image using three points for transformation.
6. **Perspective Transformation**: Applies a bird's-eye view transformation to the image.

These transformations are applied to a given image (`pratham.jpg`) and displayed using Matplotlib.

## Requirements
To run this project, you will need the following dependencies:

- Python 3.x
- OpenCV (`cv2`)
- NumPy
- Matplotlib

You can install the necessary packages with the following command:
```bash
pip install opencv-python numpy matplotlib


**Usage**
Clone or download the repository.
Ensure you have the required dependencies installed.
Replace the image path (pratham.jpg) with your desired image file in the code:

image = cv2.imread("C:/Users/Pratham.m/Downloads/pratham.jpg")
Run the script to apply the transformations and display the results:

Output
The script will display the following processed images:

Original Image
Scaled Image (50%)
Translated Image (100px right, 50px down)
Rotated Image (90° Clockwise)
Flipped Image (Horizontal)
Affine Transformed Image
Perspective Transformed Image (Bird's-eye view)
Example Output:

The images will be displayed inline using Matplotlib.
