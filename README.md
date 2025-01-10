# Visualizing CNN Filters and Feature Maps with VGG16

## Overview
This project demonstrates how to visualize the filters and feature maps of a pre-trained Convolutional Neural Network (CNN) model, VGG16. The visualizations help understand the internal workings of CNNs by showing what the network "sees" at each layer when processing an input image.

## Features
- **Filter Visualization:** Displays the weights of filters in the first convolutional layers.
- **Feature Map Visualization:** Visualizes feature maps for a given input image from various layers of VGG16.
- **Layer-wise Analysis:** Allows analysis of specific convolutional layers to understand feature extraction.

## How It Works
1. Loads the pre-trained VGG16 model.
2. Extracts and normalizes filters from convolutional layers.
3. Displays feature maps for an input image from selected layers.
4. Includes detailed visualizations for understanding the transformation of the input image through the network.

## Dependencies
- `Keras` (with TensorFlow backend)
- `matplotlib`
- `numpy`

Install dependencies using:
```bash
pip install tensorflow keras matplotlib numpy
