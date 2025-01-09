# DenseNet-121 Model for Crop Disease Detection

This repository provides an implementation of a DenseNet-121 model for detecting crop diseases. It leverages transfer learning to achieve high accuracy and includes real-time detection capabilities using a PC camera.

## Features
- **DenseNet-121 Transfer Learning**: Pre-trained DenseNet-121 model adapted for crop disease classification.
- **Real-time Detection**: Includes code for real-time detection using a webcam.
- **Saved Model**: Pre-trained model available in `.h5` format.
- **Test Images**: A sample set of test images is provided in a compressed format.

---

## Repository Structure
- `DenseNet.ipynb`: Jupyter notebook for training the DenseNet-121 model.
- `DenseNetCV.ipynb`: Jupyter notebook for real-time crop disease detection using a PC camera.
- `DenseNet121.h5`: Saved DenseNet-121 model (HDF5 format).
- `test.zip`: Compressed folder containing test images.
- `.gitattributes`: Configuration file for Git LFS to track large files.

---

## Prerequisites
- Python 3.x
- Jupyter Notebook
- Required libraries (install via `requirements.txt` if available):
  - TensorFlow
  - Keras
  - OpenCV
  - NumPy
  - Matplotlib
