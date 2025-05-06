Overview

This repository contains a deep learning-based emotion detection system that can classify facial expressions into different emotional categories. The system includes both a Jupyter notebook for model development and a real-time webcam implementation.
Project Structure

    Emotion_Detection.ipynb: Jupyter notebook containing the complete workflow for training the emotion detection model

    Emotion_Detection_WebCam.ipynb: Implementation for real-time emotion detection using webcam

    emotiondetector.h5: Pretrained model weights

    emotiondetector.json: Model architecture in JSON format

    haarcascade_frontalface_default.xml: Haar Cascade classifier for face detection

Features

    Real-time emotion detection from webcam feed

    Classifies emotions into 7 categories:

        Angry

        Disgust

        Fear

        Happy

        Sad

        Surprise

        Neutral

    Uses Convolutional Neural Network (CNN) for emotion classification

    OpenCV for face detection and video processing

Technologies Used

    Python 3.x

    TensorFlow/Keras

    OpenCV

    NumPy

    Matplotlib

    Jupyter Notebook
