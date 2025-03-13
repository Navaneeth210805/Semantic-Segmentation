# Semantic Segmentation of Aerial Drone Imagery

This repository contains a project focused on semantic segmentation of aerial drone imagery using a U-Net architecture with skip connections. The model is designed to segment 23 distinct classes from drone-captured images, effectively addressing challenges such as vanishing gradients.

## Project Overview

- **Objective:** Segment 23 classes from aerial drone images.
- **Architecture:** U-Net with skip connections to mitigate vanishing gradient issues.
- **Performance:**
  - **Training Accuracy:** 89% (Loss: 0.32)
  - **Testing Accuracy:** 75% (Loss: 1.02)

## Features

- End-to-end implementation of a U-Net based semantic segmentation model.
- Detailed performance metrics demonstrating consistent model performance on complex datasets.
- Preprocessing steps and model training routines optimized for aerial imagery.

## Requirements

- Python 3.x
- TensorFlow or PyTorch (depending on your implementation)
- NumPy, Pandas, Matplotlib

Thank you for checking out this project!