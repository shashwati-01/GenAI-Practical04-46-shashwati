# GenAI Practical 4: LSTM Sequence-to-Sequence Learning

## Objective
Implementation of an LSTM-Based Encoder-Decoder Architecture for Sequence-to-Sequence Learning.

## Description
This repository contains a TensorFlow/Keras implementation of a character-level sequence-to-sequence (seq2seq) model. The neural network is designed and trained to reverse input character strings (e.g., taking the input "hello" and predicting "olleh"). 

## Key Features
* **Automated Data Generation:** Dynamically creates a synthetic dataset of randomized character sequences for training.
* **Encoder-Decoder Architecture:** Utilizes an LSTM encoder to process input sequences into latent state vectors, and an LSTM decoder for character generation.
* **Teacher Forcing:** Implements teacher forcing during the training phase to stabilize and speed up learning.
* **Custom Inference:** Includes a standalone inference model and function to predict and reverse novel text sequences step-by-step.
