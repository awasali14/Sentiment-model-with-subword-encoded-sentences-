# Sentiment-model-with-subword-encoded-sentences

## Overview

This repository contains a TensorFlow project focused on sentiment analysis of textual data. The project uses subword tokenization to enhance model understanding of language nuances and trains a neural network to classify sentiments as positive or negative.

## Project Description

The motivation for this project was to explore advanced text preprocessing techniques like subword text encoding, which allows for a balance between character and word-level processing, thus improving model performance on sentiment classification tasks. The project demonstrates how to process and analyze text data to solve the problem of sentiment classification in a robust and scalable way.

### Problem Solved

This implementation tackles sentiment analysis, which is crucial for understanding public sentiment in data analytics, especially in areas such as customer feedback, social media monitoring, and brand reputation management. It offers an approach that is less susceptible to the issues of out-of-vocabulary words that plague typical word-level tokenizations.

### Learnings

Key insights from the project include:
- Effective use of TensorFlow and TensorFlow Datasets for data handling and preprocessing.
- Application of subword tokenization to capture more linguistic detail than word-level tokenization.
- Training a neural network in TensorFlow to perform sentiment analysis, leveraging embedding layers and dense layers.

## Setup

### Dependencies

- TensorFlow 2.0
- NumPy
- Pandas
- Matplotlib
- TensorFlow Datasets

## Data

The project utilizes a sentiment dataset that includes text and corresponding sentiment labels (positive/negative). This dataset is preprocessed using subword text encoding to convert text into a sequence of subword indices.

## Code Functionality

1. **Data Acquisition:** Downloads the sentiment dataset.
2. **Text Preprocessing:** Implements subword text encoding.
3. **Dataset Preparation:** Converts text into training and testing datasets suitable for network training.
4. **Model Architecture:** Defines and compiles a TensorFlow neural network with embedding and dense layers.
5. **Model Training:** Trains the neural network on the sentiment data.
6. **Results Visualization:** Plots training accuracy and loss graphs.
7. **Embedding Visualization:** Exports embedding vectors and metadata for visualization in the TensorFlow Embedding Projector.

## Results

The model's performance is visualized through accuracy and loss graphs, demonstrating its effectiveness in sentiment classification based on the training and validation datasets. The embeddings are also made available for further exploration and visualization of word vector space.
