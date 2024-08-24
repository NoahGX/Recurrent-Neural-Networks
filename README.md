# Recurrent Neural Networks

## Overview
The purpose of these Jupyter notebooks is to demonstrate the implementation and application of Recurrent Neural Networks (RNNs) and bi-directional RNNs in order to classify names by nationality. The models are trained on a dataset of names from various countries and predicts the nationality based on the input name.

## Features
- Implementation of RNN and bi-directional RNN models in PyTorch.
- Functions to evaluate and predict nationalities from names.
- Visualization of prediction results for different names across different models.

## Usage
Run each cell sequentially to train the model and see the predictions.

## Prerequisites
- Python 3.6 or newer
- Numpy
- PyTorch
- Matplotlib (for visualization)

## Input
The input to the model consists of names that are provided as strings. The default names of the examples included within the notebooks can be replaced with choices of users in order to test the model's predictions capabilities.

## Output
The output is the predicted nationality for each input name along with the confidence score of the prediction. Outputs are printed directly in the notebook.

## Notes
- Ensure all prerequisites are installed
- The accuracy of predictions may vary based on name and training data available for particular nationalities.
- Ensure that all paths of necessary assets and data files used by the notebooks are configured properly.