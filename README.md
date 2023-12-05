Project Title: Automatic Detection System

Project Objective:
The goal of this project is to develop an automatic detection system using image processing and machine learning techniques. The system aims to categorize images into different classes based on certain features or criteria.

Implementation Method & Results for Version 1:

Image Processing: The script imports libraries such as matplotlib, cv2 (OpenCV), numpy, and PIL (Python Imaging Library) for image manipulation and processing.
Machine Learning Framework: TensorFlow with Keras is used, indicating the use of neural networks or deep learning models.
Data Handling: The script includes functions for managing image datasets, including splitting into training, testing, and validation sets, which is a standard approach in machine learning for model training and evaluation. 60% for training, 20% for testing, 20% for validation.
Directory Structure: The code suggests a structured approach to handle image datasets, with separate directories for positive, negative, training, testing, and validation sets.
Results: Acurracy is over 97%.

Version 2 Improvements:

Refined Image Processing: Version 2 demonstrates more advanced image processing techniques, offering improved handling of input images, which enhances the performance of the final model.

Enhanced Data Handling: The creation and management of datasets in version 2 are notable. While using 40,000 images led to lower efficiency in model training in the previous version, version 2 adopts a strategy of randomly selecting a subset(10%) of images for model training. This approach, combined with cross-validation, optimizes the model more effectively.

#Dataset https://data.mendeley.com/datasets/5y9wdsg2zt/1
The dataset contains concrete images having cracks. The data is collected from various METU Campus Buildings.
The dataset is divided into two as negative and positive crack images for image classification. 
Each class has 20000images with a total of 40000 images with 227 x 227 pixels with RGB channels. 
The dataset is generated from 458 high-resolution images (4032x3024 pixel) with the method proposed by Zhang et al (2016). 
High-resolution images have variance in terms of surface finish and illumination conditions. 
No data augmentation in terms of random rotation or flipping is applied. 

