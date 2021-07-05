# Using Transfer Learning to classify different  dog breeds

## About the data

The data comes from the Kaggle dog breed identification competition ( https://www.kaggle.com/c/dog-breed-identification). It consists of a collection of 10,000+ labelled images of 120 different dog breeds (a subset of ImageNet).

## Problem description

This kind of problem is called multi-class image classification since we are trying to classify mutliple different breeds of dog. 

In particular, it will be used a pretrained model from TensorFlow Hub so as to leverage the patterns of another model which has been trained to classify images instead of training a model from scratch.

