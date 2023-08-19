# Alexnet_Implementation
Implementation of Alexnet as per the original paper.

In this [jupyter notebook file](https://github.com/archit-lahiri/Alexnet_Implementation/blob/main/alexnet.ipynb)  we implement the Alexnet architecture as it was proposed in the paper:

Krizhevsky et al., 2012. ImageNet classification with deep convolutional neural networks
https://proceedings.neurips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf

The proposed model in the paper was made as a solution to the Imagenet image classificaiton problem for the year 2010 and outperformed other competitors on top-1 and top-5. It's complete end-to-end deep learning approach with high accuracy and innovative use of two GPUs to reduce training was novel at the time and drew lots of attention to using deep learning for computer vision tasks, hence becoming a pioneer. The idea proposed in the paper- of using a series of blocks consiting of convolutional layers followed by maxpooling layers, as well as using fully connected layers after these blocks is an approach used almost universally today with different hyperparameters as required by the problem at hand.

In this implementation we will replicate the model architecture and train a dataset and observe train and validation loss and accuracy. The original dataset used was the Imagenet dataset as provided by the competition which consisted of 1.2 million images divided into 1000 classes. The model was also tested on the 2012 version of the dataset as test labels were available. As access to this dataset is restricted we will instead be using a flowers dataset freely available on Kaggle. 


