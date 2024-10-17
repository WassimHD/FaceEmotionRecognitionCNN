# Face Emotion Recognition CNN

## Overview

This project implements a deep learning model for face emotion recognition using Convolutional Neural Networks (CNNs). The model is designed to classify 7 different emotions:

- Neutral
- Happy
- Sad
- Fear
- Disgust
- Surprised
- Angry

## Technologies Used

- **Deep Learning Framework**: TensorFlow/Keras
- **Model Architecture**: MobileNetV2
- **Face Detection**: Haar Cascade algorithm
- **Testing Environment**: Webcam

## Project Description

The main goal of this project is to develop a system that can recognize human emotions based on facial expressions. By leveraging the power of CNNs, specifically the MobileNetV2 model, this project aims to create an efficient and accurate emotion recognition system.

### Face Detection

The Haar Cascade algorithm is used for detecting faces in real-time through a webcam feed. This allows the model to focus on the facial regions of interest for emotion classification.

### Emotion Classification

The model is trained to recognize and classify seven distinct emotions. Each detected face is passed through the CNN model to predict the emotion with the highest probability.

### Project Structure :

- FaceEmotionRecognitionTraining file contains all the model training life cycle
- ProjectWebCamDemi contains the live web cam demo

### NB

Before running the project, make sure to unzip the train_data.zip file
