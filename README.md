# Difference between two Images using Computer Vision

This repository provides two different methods to find the difference between two images (mostly web pages) using computer vision techniques. The methods are implemented using OpenCV and scikit-image libraries in Python.

## Method 1: Using OpenCV's absdiff function

### Overview
This method involves the following steps:
1. Importing necessary libraries.
2. Loading the two images.
3. Resizing the images for consistency.
4. Detecting differences using OpenCV's absdiff function.
5. Enhancing the difference between two input images.
6. Detecting contours and drawing bounding boxes around the differences.
7. Calculating the similarity score.
8. Saving the output images.

### Usage
To use this method, follow these steps:
1. Ensure you have OpenCV and imutils installed.
2. Run the provided Python script.
3. Provide the file paths of the input images.
4. The script will output the difference image and the similarity score.

## Method 2: Using scikit-image's structural similarity metric

### Overview
This method involves the following steps:
1. Importing necessary libraries.
2. Loading the two images.
3. Resizing the images for consistency.
4. Converting images to grayscale.
5. Detecting differences using scikit-image's structural similarity metric.
6. Applying thresholding and contour detection.
7. Drawing bounding boxes around the differences.
8. Calculating the similarity score.
9. Saving the output images.

### Usage
To use this method, follow these steps:
1. Ensure you have scikit-image, OpenCV, and imutils installed.
2. Run the provided Python script.
3. Provide the file paths of the input images.
4. The script will output the difference image, the similarity score, and a concatenated image showing input images and differences.

## Repository Structure

![image](https://github.com/Dharinesh/Difference-between-two-Images-using-Computer-Vision/assets/108059896/5fe31983-3683-4d70-9742-bd764e5e061c)


## Requirements
- Python 3.x
- OpenCV
- imutils
- scikit-image

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- The code in this repository is inspired by various tutorials, documentation, and community discussions on computer vision techniques.

