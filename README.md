# Midterm
Describe Your Dataset
URL: https://www.kaggle.com/datasets/deepcontractor/is-that-santa-image-classification

## Task:

The task of this dataset is to classify the images into the class 'Santa' and 'non-Santa'. The dataset has 1230 files which are divided into 4 directories.

test/not-a-santa: 308 files. Image of people, actors, saints, super-hero, Gandalf, etc.
test/Santa: 308 files.Image of Santa Claus
train/not-a-santa: 307 files. Image of people, actors, saints, super-hero, Gandalf, etc.
train/Santa: 307 files.Image of Santa Claus.
Datasets

## Train dataset: I used the 'train' directory to train the model.

## Validation dataset: I chose 100 files randomly from 'test' directory.

## Test dataset: I chose 100 files randomly from 'test' directory.

## Features(x):

As they are images, the input features can be differ from models. First of all, as the task is to classify Santa and non-Santa, I used classification models: logistic regression, decision tree, SVC, MLP, and CNN.

logistic regression, decision tree, SVC, MLP: linear input. The image is converted in linear vector and used as features.
CNN: The spacial information is reflected in features. It will not converted in linear form in the convolutional layer.
...

## Target(y):

Target is to find out in which class the input image is.

Santa
Non-Santa
