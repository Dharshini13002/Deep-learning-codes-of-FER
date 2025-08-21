# Deep-learning-codes-of-FER
This repository contains deep learning implementations for Facial Emotion Recognition (FER) using the FER2013 dataset. The project explores multiple architectures including CNN, LSTM, GRU, and Transformer-based models, with training, validation, and testing pipelines.

📂 Features

Dataset handling (FER2013 with train/val/test splits)

Preprocessing with PyTorch transforms (resize, normalize, augmentation)

Implementations of:

Convolutional Neural Networks (CNN)

Recurrent models (LSTM, GRU)

Transformer models for image sequences

Accuracy evaluation (train, validation, test)

Data visualization (sample images, confusion matrices, accuracy plots)

Support for GPU training with CUDA

📊 Dataset

FER2013 (Facial Emotion Recognition 2013)

7 emotion classes: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral

Grayscale images of size 48x48

🚀 Models Implemented

CNN-based classification

GRU for temporal feature extraction

Transformer encoder for sequence modeling

Transfer learning using ResNet/ViT

🧪 Results

Accuracy evaluated on train, validation, and test sets.

Comparison of different architectures.

📌 Requirements
torch  
torchvision  
numpy  
matplotlib  
scikit-learn  

📄 How to Run

Clone the repo:

git clone https://github.com/yourusername/Deep-learning-codes-of-FER.git
cd Deep-learning-codes-of-FER


Upload dataset (FER2013) or fetch from Kaggle.
LINK FOR DATASET:https://www.kaggle.com/datasets/msambare/fer2013

Run training:

python train.py
