# Machine-Translation
English to French Translation using Recurrent Neural Networks. 

## Introduction
In this notebook, a deep neural network that functions as part of an end-to-end machine translation pipeline is built. Completed pipeline will accept English text as input and return the French translation.

## Data:
You can download the data from data folder.

## Files Description:
machine_translation.ipynb: main ipython notebook describing the procesdure
machine_translation.html: html version of above ipython notebook
helper.py: includes functions for our project
README.md: read me file for he repository
data: data to be used for training and validation 

## Setup
This project requires GPU acceleration to run efficiently. 


## Install
Python 3
NumPy
TensorFlow 1.x
Keras 2.x
NLTK

## Using nbconvert from the command line
$ pip install nbconvert $ nbconvert machine_translation.ipynb


## Blog
You can find the post abou this project on the link below:
https://medium.com/@anuptukarampatil/machine-translation-english-to-french-translation-using-recurrent-neural-networks-90f8b9e1635e

## Conclusion: 
This was just the basic implementation of embedding with RNN models. We can also use bidirectinal RNNs, add more layers, train for more epochs. In this link provided, I was able to achieve more than 96 percent accuracy on vaidation data. 

## Recommendation:
This project focuses on learning various network architectures for machine translation, but we don't evaluate the models according to best practices by splitting the data into separate test & training sets -- so the model accuracy is overstated. Use the [`sklearn.model_selection.train_test_split()`](http://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html) function to create separate training & test datasets, then retrain each of the models using only the training set and evaluate the prediction accuracy using the hold out test set. Does the "best" model change?
