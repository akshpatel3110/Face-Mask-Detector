Face Mask Detection

Face Mask Detection System built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.


😇 Motivation

Amid the ongoing COVID-19 pandemic, there are no efficient face mask detection applications which are now in high demand for transportation means, densely populated areas, residential districts, large-scale manufacturers and other enterprises to ensure safety. The absence of large datasets of ‘with_mask’ images has made this task cumbersome and challenging.


⚠️ TechStack/framework used

OpenCV
Caffe-based face detector
Keras
TensorFlow
MobileNetV2


⭐ Features

Our face mask detector doesn't use any morphed masked images dataset and the model is accurate. Owing to the use of MobileNetV2 architecture, it is computationally efficient, thus making it easier to deploy the model to embedded systems (Raspberry Pi, Google Coral, etc.).

This system can therefore be used in real-time applications which require face-mask detection for safety purposes due to the outbreak of Covid-19. This project can be integrated with embedded systems for application in airports, railway stations, offices, schools, and public places to ensure that public safety guidelines are followed.

📁 Dataset

Dataset consists of 10,359 images belonging to two classes:

with_mask: 6359 images
without_mask: 4000 images
The images used were real images of faces wearing masks. The images were collected from the following sources:

Kaggle datasets
RMFD dataset
