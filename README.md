# Project Title: Breast Cancer Image Classification

## Overview
This project aims to compare two different approaches for classifying breast cancer images as benign or malignant. The two approaches involve using a Dense classifier and a pre-trained VGG16 and ResNet model for feature extraction, followed by XGBoost for the final classification. The project focuses on evaluating the performance of these two methods in terms of accuracy, speed, and resource requirements.

## Table of Contents
- [Introduction](#introduction)
- [Dependencies](#dependencies)
- [Dataset](#dataset)
- [Approaches](#approaches)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Introduction
Breast cancer is a significant health concern, and the early detection of malignant tumors is crucial for effective treatment. In this project, we explore two methods for classifying breast cancer images, with a particular focus on comparing a Dense classifier and the feature extraction capabilities of the VGG16 model. We then utilize the XGBoost algorithm for the final classification.

## Dependencies
Ensure that you have the following dependencies installed before running the code:
- Python 3.x
- TensorFlow 2.x
- Keras
- XGBoost
- Scikit-Learn
- Numpy
- Matplotlib
- Other common data science and image processing libraries

## Dataset
The dataset used for this project is not included in this repository due to its size. You can obtain the breast cancer image dataset from a reliable source and organize it into benign and malignant classes.

## Approaches
### Approach 1: Dense Classifier
The first approach involves building a custom Dense neural network that directly takes breast cancer images as input. The network is trained to classify the images into benign or malignant categories.

### Approach 2: VGG16 and ResNe + XGBoost
The second approach uses a pre-trained VGG16 model for feature extraction. The features extracted from the VGG16 model are then used as input to an XGBoost classifier for the final classification.

## Usage
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/ppremdas3/breast-cancer-classification.git
   ```

2. Set up your Python environment with the required dependencies.

3. Organize your breast cancer image dataset into benign and malignant categories and place them in a folder structure that the code can access.

4. Run the code for the selected approach (Dense Classifier or VGG16 + XGBoost) by executing the appropriate script.

## Results
The project aims to evaluate the performance of both approaches using metrics like accuracy, precision, recall, and F1-score. The results will be displayed and compared to determine which approach is more effective for classifying breast cancer images.

## Contributing
Contributions to this project are welcome. If you have suggestions for improvements, new features, or bug fixes, please open an issue or create a pull request. Make sure to follow the project's coding guidelines and the open-source license.

