# Alpaca Classification with MobileNetV2

This project uses TensorFlow and MobileNetV2 to classify images of alpacas. It applies transfer learning with fine-tuning to build a binary classification model, distinguishing between images of alpacas and other objects.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Setup](#setup)
- [Usage](#usage)
- [Results](#results)
- [Acknowledgments](#acknowledgments)

## Overview
The goal of this project is to classify images into two categories: **alpaca** and **not alpaca**. It uses MobileNetV2, a pre-trained deep learning model, to leverage transfer learning for efficient and accurate classification.

## Dataset
The dataset used in this project comes from the [Convolutional Neural Networks course by deeplearning.ai](https://www.deeplearning.ai/). It consists of two directories:
- `alpaca`: Images of alpacas
- `not alpaca`: Images of other objects

### Preparing the Dataset
1. Download the dataset from [this link](<(https://www.kaggle.com/datasets/sid4sal/alpaca-dataset-small)>).
2. Extract the dataset and ensure the directory structure is as follows:
project-directory/ ├── dataset/ │ ├── alpaca/ │ ├── not alpaca/ └── your-notebook.ipynb

The `dataset` directory must be in the same directory as the Jupyter notebook.

## Setup
### Prerequisites
- Python 3.7+
- TensorFlow 2.x
- Matplotlib

### Installing Dependencies
Install the required Python libraries using pip:
```bash
pip install tensorflow matplotlib
