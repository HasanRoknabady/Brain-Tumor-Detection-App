# Brain-Tumor-Detection-App
This repository contains the code and resources for a brain tumor detection project using MRI images. The project incorporates adaptive median filtering and contrast stretching techniques, and includes a convolutional neural network (CNN) model and a mobile application developed with TensorFlow Lite.

# Abstract
In this study, we present a novel approach to brain tumor detection using MRI that incorporates adaptive median filtering and contrast stretching techniques. Our method achieved an accuracy of 93%, a significant improvement over previous studies. We also developed a mobile app named Brainscan to enable convenient and practical brain tumor detection for users, facilitating early diagnosis and treatment.

## Introduction
Medical imaging, particularly MRI, is crucial in diagnosing brain conditions such as tumors. However, interpreting MRI images accurately can be challenging due to subtle differences in tissue density and contrast. This study addresses these challenges by leveraging advanced image processing techniques and machine learning.

## Core Material
Dataset
We used the "Brain MRI Images for Brain Tumor Detection" dataset from Kaggle, consisting of 253 grayscale DICOM images (155 with tumors and 98 normal). Due to the dataset's small size, data augmentation techniques were applied to balance and enhance the dataset for training and testing the machine learning model.

## Preprocessing Techniques
Adaptive Median Filter
Adaptive median filtering is used to reduce noise in MRI images while preserving sharp edges and important details, enhancing the clarity and accuracy of tumor detection.

## Contrast Stretching
Contrast stretching enhances the visibility of subtle differences in tissue density in MRI images, making it easier to distinguish tumors from normal tissue.

## CNN Model
Our CNN architecture is designed to detect brain tumors from MRI images. It includes several layers:

Input Layer
ZeroPadding2D Layer
Convolutional Layers
Batch Normalization Layer
ReLU Activation Layer
Max Pooling Layers
Flatten Layer
Fully-Connected Layer with Sigmoid Activation
Mobile Application: Brainscan
Brainscan is an Android app developed using TensorFlow Lite. The app allows users to detect brain tumors from images taken with the device's camera or selected from the gallery. It performs real-time inference on the device, enabling offline functionality.

TensorFlow Lite
TensorFlow Lite is a lightweight version of TensorFlow designed for mobile and embedded devices. It allows for efficient deployment of machine learning models on resource-constrained devices, making it ideal for Brainscan.

Accuracy
By implementing the CNN model and applying noise reduction and contrast enhancement on the augmented dataset, we achieved an accuracy of 93% in brain tumor detection.

Conclusion
Our study demonstrates the feasibility and effectiveness of integrating image processing techniques and machine learning for brain tumor detection. The Brainscan mobile app extends this capability to end-users, potentially enhancing early diagnosis and improving patient outcomes.

