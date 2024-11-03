# EagleViewCodility
It is about parallel processing an image and counting the pixels above some value

Miultiple thread proce
# Please find the code at imageProcessing/imageProcessing/imageProcessing.cpp
# OpenCV Image Processing Project

## Overview
This project processes a set of images in parallel using OpenCV. It creates binary mask images where all three color channels (Red, Green, and Blue) have values above 200. The masks are then saved as lossless PNG files, and the total number of pixels that meet the criteria across all images is logged in a text file.

## Features
- **Parallel Processing**: Utilizes OpenMP for parallel processing of images, enhancing performance.
- **Binary Mask Generation**: Creates a binary mask for each image based on channel values.
- **Pixel Counting**: Counts and logs the total number of pixels across all images that meet the specified criteria.
- **File Management**: Supports both JPG and PNG file formats.

## Requirements
- C++ compiler that supports C++17 (for `std::filesystem`)
- OpenCV library
- OpenMP for parallel processing
- CMake (optional, for building the project)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
