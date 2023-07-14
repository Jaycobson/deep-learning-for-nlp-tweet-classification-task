# Toxic Comments Analysis and Classification in NLP
This repository contains code and resources for performing toxic comments analysis and classification using various deep learning models in Natural Language Processing (NLP).

## Overview
Toxic comments analysis is a critical task in NLP that involves identifying and classifying offensive or harmful content in online discussions. This project focuses on utilizing deep learning models to automatically classify text comments into toxic or non-toxic categories based on their content.

## Features
Implementation of different deep learning architectures for toxic comments classification.

Preprocessing techniques such as tokenization, padding, and embedding.

Training and evaluation of the models using benchmark datasets.

Model performance analysis and comparison.

Models and Results


The repository includes the following deep learning models, ranked by their performance based on AUC score:

Bi-directional LSTM: This model achieved the highest AUC score among the models implemented. It leverages the bidirectional nature of LSTM to capture contextual information in both forward and backward directions.

GRU (Gated Recurrent Unit): The GRU-based model achieved slightly lower performance compared to the Bi-directional LSTM. It has fewer parameters and is computationally efficient while still capturing sequential dependencies.

LSTM (Long Short-Term Memory): The LSTM model performed slightly lower than the Bi-directional LSTM and GRU models. It excels at capturing long-term dependencies and has been widely used in various NLP tasks.

Simple RNN (Recurrent Neural Network): The Simple RNN model achieved the lowest performance among the implemented models. It struggles with capturing long-term dependencies and may suffer from the vanishing gradient problem.



## Requirements
Python 3.7 or above

TensorFlow 2.x

NumPy

Pandas

Matplotlib



Feel free to experiment with different deep learning architectures, optimization techniques, or pre-trained embeddings.
Extend the functionality of the project by implementing additional models, incorporating ensemble methods, or exploring advanced techniques for toxic comments analysis.
