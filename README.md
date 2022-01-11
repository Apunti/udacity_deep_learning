# Introduction

# Installation Guide

The python packages you will be needing are:
- jupyter
- matplotlib
- numpy
- pandas
- opencv
- torch
- tqdm


I would recommend to create a virtual environment and installing them via if you are working
with Linux (assuming you have python 3, pip and virtualenv installed, check [here](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/) instead):

```
python3 -m venv env
source env/bin/activate
python -m pip install -r requirements.txt
```
Once you have installed all the dependencies you should be able to run the notebooks.

# Projects

### Project 1 - Bike Sharing

In this project, you'll build your first neural network and use it to predict daily bike rental ridership. 
We've provided some of the code, but left the implementation of the neural network up to you (for the most
part). After you've submitted this project, feel free to explore the data and the model more.

The model is used from scratch with `numpy`.

### Project 2 - Dog Breed Classification
In this project, you will learn how to build a pipeline to process real-world, user-supplied images. Given 
an image of a dog, your algorithm will identify an estimate of the canine’s breed. If supplied an image of 
a human face, the code will identify the resembling dog breed.

### Project 3 - TV Script Generator
In this project, you'll generate your own Seinfeld TV scripts using RNNs. You'll be using a Seinfeld dataset 
of scripts from 9 seasons. The Neural Network you'll build will generate a new, "fake" TV script.

### Project 4 - Face Generator
In this project, you'll use generative adversarial networks to generate new images of faces.
