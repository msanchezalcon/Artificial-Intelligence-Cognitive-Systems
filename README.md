## Visual Question-Answering Project for the AICS course (MLT LT2318)


## DESCRIPTION AND PIPELINE
For this project we are using the v2.0 dataset and a classical CNN-LSTM model where image features and language features are computed separately and combined together and a multi-layer perceptron is trained on the combined features. Image features are from a pretrained network. Question features are come from Word2Vec (from Stanford) called Glove.

## Table of contents:

1. We load the libraries

2. We load the image embeddings (trained on MSCOCO dataset)

3 .Getting image features

4. Getting text features (v2.0 dataset). We load word Embeddings. We upload the spacy English model for Glove vectors and try the embeddings with examples.

5. VQA Model - LSTM

6. VQA Model - LSTM with attention

7. Train both vqa models

8. Compare performance
