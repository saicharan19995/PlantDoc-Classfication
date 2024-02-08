
# PlantDoc Classification

The project involves classification of the dataset based to their respective classes, based on the label using Custom CNN and Pre-trained DNN models. This project will be implemented using python by training and validating the dataset to compare between the models.

### Introduction

The goal of this project is to assist farmers in promptly identifying plant diseases by utilizing intelligent computer programs. We have a large collection of images showing sick plant leaves, including those from tomatoes and apple trees. The goal is to train the computer to identify these illnesses from the images. We are experimenting with various sophisticated models, which can be thought of as highly intelligent computer brains, to determine which performs best.
By doing this, we want to develop a tool that can determine whether plants are sick by analyzing images of their leaves. In this manner, farmers are able to ensure that their crops grow well and maintain their health at an early stage. For farmers, it’s like having a plant-problem-spotting helpful friend.
The project involves classification of the dataset based on their respective classes, based on the label using Custom CNN and Pre-trained DNN models. This project was implemented using python by splitting the whole dataset into 3 parts as training, validation and testing dataset which is used throughout the course of training a model. In this project we experimented to classify the dataset using ResNet, Inception and Custom CNN model, for the DNN model we used pre-trained dataset to determine the class and train the model more efficiently. Before training the dataset it was pre-processed to remove any noise from the images so that the DNN model can recognize the area of interest precisely. The training data was saved after preprocessing so that it could be used for faster use.

### Prerequisites
    1.tensorflow
    2.keras
    3.numpy
    4.pandas
    5.matplotlib
    6.pandas

### To Run
```
python3 PlantDoc_Classification.ipynb
```