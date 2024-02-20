# Emotion Detection with CNN

## Description
This repository contains code for training a Convolutional Neural Network (CNN) model to detect emotions from facial images. The model is trained using the FER2013 dataset and utilizes packages such as numpy, OpenCV, Keras, TensorFlow, Pillow, and Kaggle.

## Installation
- Install the required packages using the following commands:
pip install numpy -- 
pip install opencv-python -- 
pip install keras -- 
pip3 install --upgrade tensorflow -- 
pip install pillow -- 
pip install kaggle -- 

## Usage
### Train Emotion Detector
- Run the following command:
py TranEmotionDetector.py

Training may take several hours depending on your processor. After training, you will find the trained model structure and weights stored in your project directory as `emotion_model.json` and `emotion_model.h5`. Copy these two files, create a `model` folder in your project directory, and paste them there.

### Run Emotion Detection Test
- Run the following command:
py TestEmotionDetector.py
