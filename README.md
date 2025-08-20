# 🐶 Dog Breed Classification Project

Welcome to the Dog Breed Classification repository! This project uses image classification techniques to identify whether an image contains a dog, and if so, predicts the breed using a pretrained CNN model. It's part of a hands-on learning journey in Python, machine learning, and image recognition.

## 📌 Project Overview

This project:
- Loads and processes image data using PIL and torchvision
- Uses a pretrained CNN (e.g., ResNet, VGG) to extract features
- Compares classifier output with known labels
- Determines whether the image contains a dog
- Evaluates model performance using accuracy metrics

## 🧠 Key Concepts

- Python dictionaries for storing results
- Label matching logic for classifier outputs
- File reading and string parsing
- Image classification using transfer learning
- Writing clean, commented, and maintainable code


## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Pillow
- torchvision
- numpy

Arguments:

- --dir: Directory containing images
- --arch: CNN architecture (resnet, alexnet, vgg)
- --dogfile: Text file with valid dog breed names
  
📊 Output

The program prints:
- Number of images
- Number of dog images
- Classification accuracy
- Misclassified dogs and breeds (optional

🛠️ In Progress

- Improving label matching logic
- Adding support for more CNN architectures
- Enhancing output formatting and visualization
  
🙌 Acknowledgments

This project is part of the Udacity AI Programming with Python Nanodegree. Special thanks to the open-source community and pretrained models from PyTorch.
