Facial-Emotion-Recognition: Research on Different CNN Architectures
This repository presents a comparative research project on Facial Emotion Recognition (FER) using various Convolutional Neural Network (CNN) architectures. The project evaluates and contrasts the performance of multiple deep learning models in detecting and classifying human emotions from facial expressions.

🧠 Objective
The primary goal is to explore and benchmark different CNN-based models for the task of facial emotion recognition, focusing on performance, accuracy, and efficiency across architectures.

📁 Project Structure
File/Notebook	Description
Base_model.ipynb	A simple baseline CNN model for initial experimentation and benchmarking.
Dense Net.ipynb	Implementation and training of DenseNet architecture for FER.
Highway Net.ipynb	Utilizes Highway Networks for improved information flow in deep layers.
Pyramidal Net.ipynb	Pyramidal network structure with gradually decreasing feature maps.
VGG 16.ipynb	Transfer learning approach using pretrained VGG-16 for emotion recognition.
Wide ResNet.ipynb	Wide Residual Network implementation for deeper representation and learning.
trainmodel.ipynb	Unified notebook for training different models and comparing performance.
realtimedetection.py	Real-time emotion detection using webcam and the trained model.
emotiondetector_latest.json	Contains the model configuration or label mapping used for real-time detection.
pretrained_for_dense_net.ipynb	Notebook for loading and evaluating pretrained DenseNet model.
README.md	This documentation file.
