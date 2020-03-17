## Visual Question-Answering Project for the AICS course (MLT LT2318)


## DESCRIPTION AND PIPELINE
For this project we are using the v2.0 dataset and a classical CNN-LSTM model where image features and language features are computed separately and combined together and a multi-layer perceptron is trained on the combined features. Image features are from a pretrained network. Question features are come from Word2Vec (from Stanford) called Glove.

## Table of contents:

We load the libraries

We load the image embeddings (trained on MSCOCO dataset)

Getting image features

Getting text features (v2.0 dataset). We load word Embeddings. We upload the spacy English model for Glove vectors and try the embeddings with examples.

VQA Model - LSTM

VQA Model - LSTM with attention

Train both vqa models

Compare performance
