# Action Detection using MediaPipe Holistic

This repository contains Python Jupyter files for action detection using MediaPipe Holistic. 

## Overview

The primary purpose of this project is to detect actions using the MediaPipe Holistic framework. It utilizes a labeled dataset provided in a CSV file (`Label.csv`). The number of signs to be trained can be specified by making changes in the `Label.csv` file.

## Getting Started

To begin, make changes in the (`Label.csv`),then , follow these steps:

1. Run the `Input.ipynb` Jupyter file:
   - This file is responsible for building the training folder structure and capturing data.
   - Execute this file to start capturing data for training.

2. Run the `train.ipynb` Jupyter file:
   - This file trains the data using an LSTM model.
   - Upon successful training, an `.h5` model file will be generated.

3. Run the `Sign.ipynb` Jupyter file:
   - This file is used to detect actions based on the trained model.
   - Execute this file to observe the detection of actions.

## Usage

Ensure you have the necessary dependencies installed before running the Jupyter files. You can install the required packages using:
