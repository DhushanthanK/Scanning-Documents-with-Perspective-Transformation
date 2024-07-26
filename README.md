# Scanning Documents with Perspective Transformation using Python OpenCV

This project demonstrates how to preprocess, detect edges, and perform perspective transformation on document images using Python and OpenCV. The goal is to transform a scanned document image into a top-down view, making it easier to read and analyze.

## Project Overview

1. **Image Preprocessing**:
   - Resized the input image for consistent processing.
   - Converted the image to grayscale for simplification.
   - Applied Gaussian blur to reduce noise and smooth the image.

2. **Edge Detection**:
   - Used the Canny edge detection algorithm to identify edges in the image.
   - Extracted contours from the edge-detected image and selected the largest quadrilateral contour, which represents the document's edges.

3. **Perspective Transformation**:
   - Reordered the contour points to align them correctly.
   - Applied perspective transformation to obtain a top-down view of the document.

4. **Post-Processing**:
   - Converted the perspective-transformed image to grayscale.
   - Applied Gaussian blur to the transformed image to enhance visual clarity.
   - Displayed the results for review.

## Technologies Used

- **OpenCV**: For image processing tasks including resizing, blurring, edge detection, and perspective transformation.
- **NumPy**: For numerical operations and handling arrays.
- **Matplotlib**: For visualizing images and results.
- **Jupyter Notebook**: For interactive development and documentation.

## How to Run

1. **Install Dependencies**:
   Make sure you have the required Python packages installed. You can install them using pip:

   ```bash
   pip install numpy matplotlib opencv-python


