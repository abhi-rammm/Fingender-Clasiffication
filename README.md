This repository contains a Python-based solution for fingerprint classification using Convolutional Neural Networks (CNNs). The model processes grayscale fingerprint images, categorizes them based on gender (male or female), and achieves high accuracy. The dataset used for training and testing is the SOCOFing dataset, which contains real and altered fingerprint images. Data preprocessing involves resizing images to 96x96 pixels and normalizing pixel values to ensure compatibility with the CNN model. Labels are extracted from the image filenames, which encode attributes like gender, hand (left or right), and finger type.

The model architecture includes two convolutional layers followed by max-pooling layers, flattening, and dense layers for classification. It employs the ReLU activation function and uses the Adam optimizer for training with a categorical cross-entropy loss. Early stopping is implemented to prevent overfitting. The model achieves exceptional accuracy during both training and evaluation, as evidenced by the provided training logs. This project demonstrates the effectiveness of CNNs for biometric classification tasks and serves as a foundational example for further exploration in image-based machine learning tasks. 