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

## Sample outputs generated:
### <Original Image> -- <Altered Image> -- <Code Output>

1. Output 1
<img src="https://github.com/Dharinesh/Difference-between-two-Images-using-Computer-Vision/assets/108059896/34bd3e70-8332-49d8-95bf-97d74911e428" width="800">

## Repository Structure

<img src="https://github.com/Dharinesh/Difference-between-two-Images-using-Computer-Vision/assets/108059896/5fe31983-3683-4d70-9742-bd764e5e061c" alt="Repository Structure" width="400">

## Requirements
- Python 3.x
- OpenCV
- imutils
- scikit-image

## How to Run the Project

### 1. Clone the Repository

- Clone or download the repository from GitHub to your local machine.

### 2. Install Dependencies

- Ensure you have Python 3.x installed on your system.
- Open a terminal window and navigate to the project directory.

```bash
cd /path/to/Difference-between-two-Images-using-Computer-Vision
```

### Install the required packages using the following command:
```bash
pip install -r requirements.txt
```
### Choose a Method:
- Decide which method you want to use for finding the difference between two images: Method 1 or Method 2.

### Prepare Input Images:
- Place your input images in the 'input/' directory inside the project folder.
- set the path of the original image to imageA variable and altered image path to the imageB variable in both the methods.
- you can customize the output image's name and location in the code.

### Run the script

### View the results:
- The results can be viewed in the output folder.
- for better viewing the difference there is a code snipper to concatenate the images to see the original, altered and the found difference image side by side.

### Explore further:
- You can explore the code to understand the implementation details of each method.
- Customize the code or integrate it into your own projects as needed.
  
## License
This project is licensed under the GNU License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- The code in this repository is inspired by various tutorials, documentation, and community discussions on computer vision techniques.

