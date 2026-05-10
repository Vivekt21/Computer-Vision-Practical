# Computer-Vision-Practical
Computer Vision and Image Analysis
Here are the files you need to set up your GitHub repository cleanly and professionally.

1. README.md
This file provides an overview of your repository, explains what each lab does, and tells others (or your future self) how to run the code.

Markdown
# Computer Vision and Image Analysis (CS342) - Lab Assignments

This repository contains the Python and Jupyter Notebook implementations for the CS342 Computer Vision and Image Analysis lab assignments. The coursework covers fundamental image processing techniques, feature extraction, and deep learning using Convolutional Neural Networks (CNNs).

## 🚀 Setup and Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Vivekt21/Computer-Vision-Practical.git](https://github.com/Vivekt21/Computer-Vision-Practical.git)
   cd Computer-Vision-Practical
Create a virtual environment (Recommended):

Bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
Install the required dependencies:

Bash
pip install -r requirements.txt
Launch Jupyter Notebook:

Bash
jupyter notebook
# 📂 Project Structure & Lab Summaries
# Lab Assignment 1: Classical Image Processing
Dataset: Caltech-UCSD Birds-200-2011 (CUB-200-2011)

segmentations.tgz(https://data.caltech.edu/records/65de6-vp158/files/segmentations.tgz)

CUB_200_2011.tgz(https://data.caltech.edu/records/65de6-vp158/files/CUB_200_2011.tgz)

Tasks:

Automated downloading and extraction of the CUB-200-2011 dataset and ground truth masks.

Image Segmentation: Implementation of Otsu's Thresholding and K-Means Clustering.

Evaluation: Calculating Intersection over Union (IoU) and Dice Coefficient against ground truth data.

Edge Detection: Comparing Sobel operators with the Canny Edge Detector for optimal edge localization and noise reduction.

# Lab Assignment 2: CNN Architecture & Feature Visualization
Model: Pre-trained VGG16 (ImageNet)

Tasks:

Theoretical analysis of VGG architecture (filter sizes, parameters, activation functions).

Extracting and visualizing filter coefficients from the first convolutional layer.

Passing an image through the network to visualize the corresponding feature map responses.

Analyzing the frequency response (2D FFT) of filters to categorize them as High-Pass or Low-Pass.

# Lab Assignment 3: Transfer Learning & Fine-Tuning
Model: Pre-trained VGG16

Tasks:

Transfer Learning: Using the ImageNet-trained VGG16 to predict classes of random CUB-200-2011 bird images and comparing the granularities of the predictions.

Network Reconfiguration: Modifying the final fully connected layer of the VGG16 architecture to output 200 classes (specifically for the CUB dataset) instead of the default 1000 ImageNet classes.
