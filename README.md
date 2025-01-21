# Image Classification using Convolutional Neural Networks (CNN)

This project performs image classification to distinguish between images of cats and dogs using a Convolutional Neural Network (CNN). The dataset used is the Cats vs. Dogs dataset from Kaggle.

## Dataset Instructions

This project uses the Cats vs. Dogs dataset from Kaggle. Since the dataset contains a large number of images (8000 for training and 2000 for testing), it is not included in this repository. Follow the steps below to download and use the dataset.

### Steps to Get the Dataset

### Download the Dataset:

Visit the Kaggle dataset page: Cats vs. Dogs Dataset.

Download the dataset as a .zip file.

### Extract the Dataset:

Extract the contents of the downloaded .zip file.

Place the training_set and test_set folders in a directory within this project.

## Dependencies
TensorFlow

Keras
## Model Architecture
### Input Layer: 
Takes images of size 64x64.
### Convolutional Layers:
Two convolutional layers with 32 filters each, followed by max-pooling layers.
### Flatten Layer:
Flattens the output from the convolutional layers.
### Fully Connected Layers:
A dense layer with 128 units and ReLU activation, followed by an output layer with a single unit and sigmoid activation.
## Training
The model is trained for 25 epochs using binary cross-entropy loss and the Adam optimizer. The training and validation accuracies are observed to improve over the epochs.

## Prediction
The trained model is used to classify a single image of a cat or a dog. The image is preprocessed, and the prediction is made using the trained model.

## Usage
### Clone the repository:
### bash
#### git clone https://github.com/Abarna-mouli/Image-Classification-using-Convolutional-Neural-Networks-CNN-.git
### Navigate to the project directory:
### bash
#### cd Image-Classification-using-Convolutional-Neural-Networks-CNN-
1.Ensure the dataset is placed in the correct directories (training_set and test_set).
 
2.Open and run the Jupyter notebook Cat_Dog.ipynb to train the model and make predictions.
