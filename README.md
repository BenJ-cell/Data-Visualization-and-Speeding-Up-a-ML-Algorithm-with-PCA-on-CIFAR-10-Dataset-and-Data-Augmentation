# Data-Visualization-and-Speeding-Up-a-ML-Algorithm-with-PCA-on-CIFAR-10-Dataset-and-Data-Augmentation

Visualizing the CIFAR - 10 data using PCA keeping the 2 first principal components containing maximum variance.

Then applying PCA to keep 90% of the explained variance with 99 components and training a deep neural network for image classification with and without PCA.

It seems that using PCA allows faster computation and better validation accuracy as we are less prone to overfitting deleting the noise induced by the less important components of the PCA.

Then to compare with a good model, we use data augmentation for generalization and a convolutional neural network on the images to classify them, we get an accuracy of 88%
