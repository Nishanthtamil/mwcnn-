# MWCNN for Image Restoration

This repository contains the code for implementing a Multi-Level Wavelet Convolutional Neural Network (MWCNN) for image restoration. The dataset used for this project is the Kaggle Wildlife Animals dataset, where the images have been artificially noised and then split into training and testing sets.

## Table of Contents
- Introduction
- Dataset
- Model Architecture
- Usage
- Results
- Contributing
- License

## Introduction
This project is part of a research effort aimed at improving image restoration processes. The MWCNN model leverages wavelet transforms to enhance the quality of restored images.

## Dataset
The dataset used in this project is sourced from Kaggle's Wildlife Animals dataset. The images are noised and then split into training and testing sets. The images are in RGB format with dimensions of 224x224 pixels. It is advised to adjust the dimensions when working with different datasets.

## Model Architecture
The model includes Discrete Wavelet Transform (DWT) and Inverse Discrete Wavelet Transform (IDWT) layers to process the images. The architecture is designed to effectively denoise and restore images.

## Usage
To use this repository, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Nishanthtamil/mwcnn.git
   cd mwcnn
2. Install the requirements:
   ```bash
   pip install -r requirements.txt
   cd mwcnn
## Results
The model has shown promising results in restoring noised images. Detailed results and performance metrics will be added soon.

## Contributions
Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.
