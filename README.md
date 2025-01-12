# Food Recognition and Nutritional Analysis

## Overview
This project implements a food recognition system that classifies images of food items and provides nutritional information for the identified food. The solution leverages TensorFlow, MobileNetV2, and additional tools for image preprocessing, data augmentation, and model evaluation.

## Features
- Food Image Classification:  Recognizes food items using a convolutional neural network (CNN) built on MobileNetV2.
- Nutritional Information Lookup: Fetches and displays nutritional information for the identified food items from a preloaded CSV file.
- Data Augmentation: Applies techniques like rotation, zoom, and horizontal flips to enhance model robustness.
- Visualization: Displays sample images and training metrics.

## Dependencies
- Python 3.x
- TensorFlow 2.x
- NumPy
- Pandas
- OpenCV
- Matplotlib

## Visualizations
- Sample Images: Displays a 3x3 grid of images with their predicted labels.
- Training Metrics: Plots training and validation accuracy/loss for monitoring model performance.

## Results
After training, the model achieves a validation accuracy and loss that reflects its performance on unseen data. Adjust epochs and batch size for improvements.

## Future Enhancements
- Extend the nutrition database for better coverage.
- Add support for more complex food classes using transfer learning.
- Optimize for real-time predictions.

## Credits
This project uses TensorFlow and MobileNetV2 pre-trained on ImageNet for feature extraction, with custom layers added for fine-tuning the food classification task.
