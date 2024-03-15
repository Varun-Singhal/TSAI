### Identifying Digits Over MNIST Dataset
___
#### Overview
This project implements a Convolutional Neural Network (CNN) model for the classification of handwritten digits using the MNIST dataset. The MNIST dataset consists of 28x28 grayscale images of handwritten digits (0-9) and is a widely used benchmark dataset in the field of machine learning.

#### Following is the repository structure:
* Session_5_assignment.ipynb - Colab file, which is the head of the project in which all other files are imported and used.
* models.py - Python file, which contains the arhitecture of the neural network we are using. 
* utils.py - Python file, which contains utility functions (train and test) necessary for the NN. 

#### Instructions to run:
  1. Download the code files and upload them in your google drive.
  2. Open the colab file and replace the URL as per your drive structure

     ```python
     sys.path.append("/content/drive/MyDrive/Colab_Notebooks/Session_5")
     ```
     
  3. Run all the cells in the colab and play around with no of epochs.
  4. Observe the accuracy graph.

#### Result
The model is trained for 2 epochs gaining the accuracy upto 98.5%, with change in learning rate in every epoch. If we increase the number of epochs and change the steps after which the learning rate should change, we will end up having a much better accuracy.
