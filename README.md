# DogorCat
Image Classifier CNN Dogs vs Cats

Image identification and classification using neural networks and machine learning.

Dataset: 
I have used the kaggle image dataset with 25k images of both cats and dogs to train a classification model built using tensorflow. It achieves around 84% accuracy. Further I have implemented data augmentation techniques to improve the accuracy to 88%. 

Few important characteristics of the Convolutional Neural Network model used to solve this problem are.. 
Dataset Division ( 95% Training set, 2.5% Validation set, 2.5% Test set)
> 4 Convolution layers, 
> 2 Fully connected layers, 
> Adam optimizer used at every convolution layer, 
> ReLu activation being used in between the 2 fully connected layers in the end.
> I have Augmented original dataset by generating linear transformations of images of cats and dogs to increase training data.
> I have developed this model just using tensorflow( without high level libraries like keras). 
 Architecture of the Convolutional Neural Network Classification Model is pictorially represented using an image in repository 
 
 Performance and Visualization using TensorBoard: Image in repository
 

Tensorboard logs of this neural network model and source code in python is available in this repository for reference.
