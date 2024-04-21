# Image Line Segmentation using OpenCV
This repository provides Python code for segmenting lines of text in an image using OpenCV. The process involves several steps, including binarization, horizontal projection profiling, and peak detection to extract the lines of text from the image.

**Requirements**

To run the code in this repository, you need to have the following libraries installed:

OpenCV
NumPy
scikit-image
Matplotlib

**Usage**

Clone the repository to your local machine:
git clone https://github.com/your-username/image-line-segmentation.git
Navigate to the repository directory:
cd image-line-segmentation
Run the Python script line_segmentation.py:
python line_segmentation.py

**Methodology**

The line segmentation process consists of the following steps:

Binarization: Convert the input image to binary format using thresholding techniques to separate text from the background.
Horizontal Projection Profiling: Calculate the horizontal projection profile (HPP) of the binarized image to identify regions with significant text content.
Peak Detection: Find peaks in the HPP to determine potential line boundaries.
Text Extraction: Optionally, extract text from the segmented lines using other OCR libraries or methods.

**Sample Output**

The output of the line segmentation process includes visualizations of the binarized image, horizontal projection profile, and segmented lines.
