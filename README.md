# News_Classification_using_LSTM

This repository contains the implementation of an NLP-based **Text Classifier** that classifies a set of News into multiple categories. It is developed using `TensorFlow`, `LSTM`, `Keras`, `Scikit-Learn`, and `Python`. The goal of this project is to perform Natural Language Processing (NLP) over a collection of texts compiled from BBC News, teach the classifer about the text features, and determine the appropriate class given a news text from a test dataset. 

The classifier designed in this project is a deep neural network with one `Embedding` layer, two `LSTM` layers, and one output `Dense` layer. The optimzer and the loss function chosen for the model are `Adam` and `sparse_categorical_crossentropy` respectively.


## Problem Statement

- The News Agency trying to cope up with the changing world.
- They want to maintain a central database of all the news. And, extra emphasis on categorizing the news into different sections.


## Objective

- The model should be able to classify the category of the news article given a text sequence
- The idea is to create a mobile app for reading news.
- They are planning on creating a user-friendly app that shows only what the user wants to see.


## Dataset

The dataset contains 7 columns REF_NO, category, Headline, author, link, date, and a short description.
There are about 160683 rows of data points in the train set.
There are about 40172 rows of data points in the test set.


## Usage

To run this project, open the notebook in Google Colab and start executing each cell as instructed. The notebook contains how to upload the data from google drive.

## Evaluation

The following figure shows how training and validation accuracy change over epochs during the training process. It also represents the changes in training and validation loss over the training epochs.

![Accuracy and loss changes over training epochs](https://github.com/kayanmorshed/BBC-News-Classification-using-LSTM-and-TensorFlow/blob/main/evaluation/training_evaulations.png)


## Conclusion

This NLP-based News Classifier can be used to categorize any sets of news texts and determine the appropriate category of an unknown news.   
