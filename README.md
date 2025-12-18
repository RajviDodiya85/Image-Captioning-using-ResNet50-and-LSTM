Image Captioning is a key problem in Computer Vision and Natural Language Processing (NLP) where the goal is to automatically generate meaningful textual descriptions for images.
This project presents an AI-based Image Captioning system that combines ResNet50 for image feature extraction and LSTM (Long Short-Term Memory) networks for sequence generation.

The model is trained and evaluated on the Flickr8k dataset and uses Beam Search with a penalty mechanism to improve caption diversity and handle rare words effectively.

 Key Features

Uses ResNet50 (pre-trained on ImageNet) for robust image feature extraction

Employs LSTM-based language modeling for caption generation

Implements Beam Search for better sentence quality

Penalizes rare/unusual words to improve caption fluency

Evaluated on the Flickr8k dataset

Produces more accurate, diverse, and natural captions

Model Architecture

Image Encoder

ResNet50 CNN

Extracts high-level visual features from images

Caption Decoder

LSTM network

Generates captions word-by-word using extracted features

Caption Generation

Beam Search algorithm

Rare-word penalty for improved diversity

Dataset

Dataset Name: Flickr8k

Description: Contains 8,000 images, each with 5 human-annotated captions

Source: Kaggle

 Dataset Link:
https://www.kaggle.com/datasets/adityajn105/flickr8k

 Technologies Used

Python

TensorFlow / Keras

NumPy

Matplotlib

ResNet50 (CNN)

LSTM (RNN)

Jupyter Notebook
