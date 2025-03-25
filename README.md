## Crack Detection Project

Overview

This project focuses on detecting cracks in concrete surfaces using machine learning and computer vision techniques. The goal is to automate the identification of cracks to improve infrastructure maintenance and safety.

Features

Image Processing: Preprocessing techniques such as grayscale conversion, edge detection, and thresholding.

Deep Learning Model: Utilizes YOLO-v5 model trained on crack images.

Dataset: A collection of labeled images of cracked and non-cracked surfaces.

Prediction Output: Model classifies input images as cracked or non-cracked.

## Dataset

The dataset consists of images of concrete surfaces with and without cracks. It has been preprocessed to enhance model performance. 
The original dataset is from https://www.kaggle.com/datasets/arnavr10880/concrete-crack-images-for-classification.
For training, we use preprocessing techniques to detect the cracks on images and then create a scrpit to create bounding boxes and label them as cracks.
