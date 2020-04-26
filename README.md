# Multi-class-text-classification
## Introduciton 
Code for an in-class kaggle competition for Deep Learning and Applications at HEC Montreal. See: https://www.kaggle.com/c/hecmontrealdeeplearningcourse

This competition consider scientific papers from different domains. The goal is to predict the domain of test papers based on their titles.

## Dataset 
The dataset is constructed from the DBLP database, where collects a set of papers from five different research domains (i.e., machine learning, natural language processing, data mining, database, programming language). The goal is to predict the categories of papers. We have provided several files, and below is a description.

1. train.csv. This file provides a number of paper ids and the corresponding labels, which can be used for training.

2. test.csv. This file provides the paper ids for evaluation.

3. text.csv. This file provides the title of each paper, which allows you to do prediction based on those titles.

## Model and result 
In this project, I used 2 state-of-art models to implement mutil-class-text-classification task. The model name and performance can be seen from follows: 

1. An attendtion based recurrent neural network (RNN) with multiple bidirectional LSTM layers. 70.8% accuracy in the test data.

2. Bidirectional Encoder Representations from Transformers or BER. 73.8% accuracy in the test data, while traning time is much longer comapared with last model.


