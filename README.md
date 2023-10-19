## Breast Cancer Classification using InceptionV3

This repository contains a deep learning-based approach to classify breast cancer images as benign or malignant using the InceptionV3 architecture.

### Overview:
The code in this repository trains an InceptionV3 model to classify images of breast cancer as either benign or malignant. The Keras library is used to facilitate the building, training, and evaluation of the model.

### Requirements:
- Keras
- Matplotlib
- NumPy

### Data Structure:
Ensure your dataset is structured as:
```
Breast_Cancer_Event_Dataset
|__ TRAIN
   |__ benign
   |__ malignant
|__ VAL
   |__ benign
   |__ malignant
|__ TEST
   |__ benign.jpg
   |__ malignant.jpg
```

### Steps to Run:
1. Clone the repository.
2. Update the paths in the code (`train_data_dir`, `validation_data_dir`, etc.) according to the directory where you've stored the dataset.
3. Run the Python script to start training the model.
4. After training, the model will predict the class of two test images (`benign.jpg` and `malignant.jpg`) and display the images along with their predictions.

### Results:
The code trains the model for 30 epochs, after which you should be able to see the training and validation accuracy and loss plots. In the end, predictions for two test images (`benign.jpg` and `malignant.jpg`) are displayed, demonstrating the model's capabilities.

### Note:
This code is a simple demonstration and may require further optimization and tweaks for real-world, large-scale datasets.

The goal of this tutorial is to build a deep learning classifier to accurately differentiate between the two.

You'll need a computer with the following installed:

Tensorflow (https://www.tensorflow.org)
Keras library (https://keras.io)
Jupyter (http://jupyter.org)
Download the x-rays provided in .zip file
