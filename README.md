# Image Caption Generator using CNN and LSTM
## Overview
- This AI project focuses on generating descriptive captions for images using a combination of Convolutional Neural Networks (CNN) and Long Short-Term Memory networks (LSTM).
- The model is trained on the Flicker8k dataset obtained from Kaggle, which contains a diverse set of images along with corresponding captions.
- Dataset link - https://www.kaggle.com/datasets/adityajn105/flickr8k

## Features
- CNN-LSTM Architecture: The model leverages the power of CNNs to extract relevant features from images and LSTM networks to generate coherent and contextually rich captions.
- Training and Testing on Flicker8k Dataset: The Flicker8k dataset from Kaggle is used for both training and testing the model. This dataset consists of images with associated captions, providing a robust foundation for developing a sophisticated image captioning system.
- Evaluation Metrics: The model's performance is assessed using standard evaluation metric - BLEU score ensuring a comprehensive analysis of its caption generation capabilities.

## Usage
- Data Preprocessing: The Flicker8k dataset is preprocessed to extract image features using the CNN, and captions are tokenized for training.
- Model Training: The CNN-LSTM model is trained on the preprocessed dataset to learn the relationships between images and their corresponding captions.
- Testing on Dataset: The trained model is tested on a separate subset of the Flicker8k dataset to evaluate its generalization and performance on unseen data.
- Random Image Testing: Additionally, a random image is input into the model to showcase its ability to generate captions for entirely new and unseen data.

## Results
- The project provides insights into the model's caption generation accuracy and generalization capabilities through evaluation metrics and qualitative analysis of the generated captions.
