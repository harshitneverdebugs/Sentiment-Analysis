# Sentiment Analysis on IMDB Dataset

This repository contains a complete project for performing sentiment analysis on the IMDB dataset using various deep learning models, including Simple Neural Networks, Convolutional Neural Networks (CNN), and Recurrent Neural Networks (LSTM) with Keras.

## Table of Contents

- [Installation](#installation)
- [Data Description](#data-description)
- [Preprocessing](#preprocessing)
- [Model Architectures](#model-architectures)
  - [Simple Neural Network](#simple-neural-network)
  - [Convolutional Neural Network](#convolutional-neural-network)
  - [Recurrent Neural Network (LSTM)](#recurrent-neural-network-lstm)
- [Results](#results)
- [Visualizations](#visualizations)
- [License](#license)

## Installation

To run this project, you need to have the following packages installed:

- TensorFlow
- Pandas
- NumPy
- Seaborn
- NLTK

Make sure to mount Google Drive to access the dataset.

## Data Description

The dataset used in this project is the IMDB Dataset, which contains 50,000 movie reviews labeled as positive or negative.

## Preprocessing

The data preprocessing steps involve:

1. Removing HTML tags from the reviews.
2. Converting the text to lowercase.
3. Removing special characters and stopwords.
4. Tokenizing the text and padding sequences to ensure uniform input size.

## Model Architectures

### Simple Neural Network

The first model is a simple feedforward neural network that uses an embedding layer and a dense layer to classify the reviews.

### Convolutional Neural Network

The second model uses convolutional layers to capture local features in the text.

### Recurrent Neural Network (LSTM)

The final model employs LSTM layers to capture long-term dependencies in the text data.

## Results

Each model is evaluated on the test set, and the accuracy is printed for each architecture.

## Visualizations

Loss and accuracy metrics for the models can be visualized using matplotlib to analyze the model performance over epochs.
