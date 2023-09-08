Deep Learning Neural Style Transfer (NST)

![](https://archive.org/download/deep-learning-with-py-torch/Deep%20Learning%20with%20PyTorch.png)
Table of Contents

    Introduction
    Getting Started
        Prerequisites
        Installation
    Usage
        Setting up Google Colab Runtime
        Loading VGG Pretrained Model
        Preprocessing Images
        Deprocessing Images
        Getting Content and Style Features
        Creating Style and Content Loss Function
        Training Loop
    Results
    Contributing
    License

Introduction

This repository contains a Deep Learning Neural Style Transfer (NST) project implemented using PyTorch. NST is a technique that allows you to apply the artistic style of one image to the content of another image, creating visually appealing artistic compositions.
Getting Started
Prerequisites

Before you begin, ensure you have the following requirements:

    Python 3.x
    PyTorch
    torchvision
    Git

Installation

    Clone this repository:

    bash

git clone https://github.com/parth1620/Project-NST.git

Install PyTorch and torchvision:

bash

    pip install torch torchvision

Usage
Setting up Google Colab Runtime

This project includes instructions for setting up Google Colab runtime. Refer to the notebook for detailed instructions.
Loading VGG Pretrained Model

The VGG19 pretrained model is used for this project. You can load it with the provided code.
Preprocessing Images

To preprocess images for NST, use the preprocess function. You can specify the maximum size for images.
Deprocessing Images

Use the deprocess function to convert processed images back to their original format.
Getting Content and Style Features

The get_features function extracts content and style features from the VGG model.
Creating Style and Content Loss Function

Define style and content loss functions using the provided code.
Training Loop

The training loop is included in the notebook. You can adjust hyperparameters such as learning rate, alpha, and beta to control the output.
Results

You can find the results of the NST process in the notebook. The output images will showcase the combination of content and style.
Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

    Fork the repository.
    Create a new branch for your feature or bug fix.
    Make your changes and test thoroughly.
    Submit a pull request with a clear description of your changes.
