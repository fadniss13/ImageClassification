# Image Classification

This repository contains two Jupyter Notebooks. Both download and classify the images in the MNIST Fashion Data Set using Deep Neural Networks, but one uses a simple Sequential Model and other uses a Convolutional Neural Network. Both models have a Train/Test split of 60000/10000 images. You can adjust the loss and epochs, in this case 0.25 and 5 respectively, and the model stops training when that loss is reached.

#### Simple Sequential Model  Results after 5 epochs:
- Loss: 0.296
- Accuracy: 0.876
- Mean Square Error (MSE): 27.684

#### Simple Sequential Model  Results after 4 epochs:
- Loss: 0.244
- Accuracy: 0.901
- Mean Square Error (MSE): 27.687

As we can clearly see, CNN is the superior technique for Image classification, with higher accuracy and lower lower loss eithout having to go through 5 epochs.
