# Gesture Recognition with CNN and RNN
> A project to develop a smart TV feature for recognizing gestures using a webcam to control TV functions.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- This project aims to develop a gesture recognition feature for a smart TV, allowing users to control the TV with specific hand gestures.
- Background: With the increasing use of smart home devices, gesture recognition offers a hands-free way to interact with technology, enhancing user experience and accessibility.
- Business Problem: Traditional remote controls can be inconvenient and prone to loss. Gesture recognition provides an intuitive and user-friendly alternative for controlling smart TVs.
- Dataset: The dataset consists of videos categorized into five gesture classes: thumbs up, thumbs down, left swipe, right swipe, and stop. Each video is a sequence of 30 frames, with varying image dimensions (360x360 or 120x160).

## Conclusions
- The Conv3D model with 4 layers, GlobalAveragePooling3D, and Dense layers achieved a high validation accuracy of 95.00%, demonstrating good generalization.
- The TimeDistributed Conv2D + GRU model showed high training accuracy (98.75%) but lower validation accuracy (80.00%), indicating potential overfitting due to a large number of parameters.
- The TimeDistributed MobileNetV2 + GRU model balanced performance with a high training accuracy of 98.75% and validation accuracy of 95.00%, making it suitable for real-world applications.
- Utilizing pre-trained models like MobileNetV2 significantly enhances performance and speeds up convergence, proving to be effective for feature extraction in gesture recognition tasks.

## Technologies Used
- TensorFlow - version 2.4
- Keras - version 2.4
- OpenCV - version 4.5
- NumPy - version 1.19
- Matplotlib - version 3.3

## Acknowledgements
- This project was inspired by the increasing demand for smart home automation and the need for intuitive user interfaces.
- References: Research papers on CNN and RNN architectures for video classification and gesture recognition.
- This project was based on various tutorials and documentation from the TensorFlow and Keras websites.

## Contact
Created by [@mundhranishant] - feel free to contact me!
