# flower-classifier-pytorch
Classifying 133 different dog breed from images with CNN (using pytorch)

## Project Overview
This project is the assignment from the [Udacity Deep Learning Nanodgree](https://www.udacity.com/course/deep-learning-nanodegree--nd101). 
The project focuses on training a convolutional neural network to classify 133 different dog breed
species from a set of 6000 images ([dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)). Because of the small dataset, I have utilized pre-trained models 
such as VGG19 and VGG16 and did transfer learning on top of these models to classify the dog
images with an accuracy of about 83% from the test dataset.

## Prerequisite

[Python3](https://www.python.org/downloads/)

[Jupyter notebook](https://jupyter.org/install)

[PyTorch](https://pytorch.org/get-started/locally/)


## Usage
**_Image Classifier Project.ipynb_**    

Jupyter notebook which shows the entire process from data loading 
to exploration, training, testing and validation.


**_train.py_**                          

trains the model to classify dog breed. Takes in hyperparameters as well as base model,


**_predict.py_**                        

predicts input image(s) of the top k (user input) likely flower species with corresponding 
probabilities. Takes in user input of path of trained model and path of test image to be predicted.
