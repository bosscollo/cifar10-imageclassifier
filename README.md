# CIFAR-10 CNN Image Classifier 

This project trains a Convolutional Neural Network using TensorFlow on the CIFAR-10 dataset.

##  Dataset
- CIFAR-10 contains 60,000 32x32 color images across 10 categories.

##  Model
- 3 Conv2D + MaxPooling layers
- 1 Flatten + 2 Dense layers
- Optimizer: Adam
- Loss: SparseCategoricalCrossentropy

## How to Run
1. Clone this repo
2. Run `cifar10_classifier.ipynb` in Jupyter or Colab

##  Requirements
See `requirements.txt`

##  Accuracy
~70–80% test accuracy after 10 epochs
