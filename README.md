# Artist Classification with Deep Learning

This repository contains a deep learning model for artist classification. The model is trained on a dataset of images representing various artists. Given an input image, the model predicts the likely artist associated with the artwork.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Usage](#usage)
- [Requirements](#requirements)
- [License](#license)

## Introduction

Artwork classification is a challenging task that involves identifying the artist of a given piece based on visual features. This project leverages deep learning techniques to create a model capable of accurately classifying artworks into different artist categories.

## Dataset

The dataset used for training and evaluation is available in the `dataset` directory. It includes a collection of images labeled with the corresponding artist names.

## Model Architecture

The deep learning model is implemented using [TensorFlow](https://www.tensorflow.org/) and [Keras](https://keras.io/). Details about the architecture, layers, and parameters can be found in the `model.py` file.

## Usage

To use the pre-trained model for artist classification, you can use the `predict.py` script. Simply provide the path to the image you want to classify as a command-line argument:

##Requirements

pip install -r requirements.txt

##License

This project is licensed under the MIT License.


```bash
python predict.py --image_path path/to/your/image.jpg
