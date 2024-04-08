# Image to Numbers: Python Implementation

This repository contains a Python script for generating a 6x6 image array representation from an original image and creating new images with randomized rows of colors, which can be scaled up to larger sizes.

## Overview

The script begins by loading an existing image and resizing it to a 6x6 pixel image. This smaller image is converted into a 3D numpy array representing the RGB values of each pixel. Additionally, the script includes functionality to generate new images, where each row is a random color. These generated images can also be scaled up to a specified size while maintaining the sharpness of the original pixels.

## Features

- Resize an image to a 6x6 array.
- Convert an image to a numpy array of RGB values.
- Generate images with 6 rows of random colors.
- Scale images up to larger sizes with a specified pixel dimension.

## Requirements

To run the script, you need:

- Python 3
- Pillow (PIL Fork)
- Numpy

Install the required packages using:

```bash
pip install pillow numpy
```
