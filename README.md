# MACHINE LEARNING JUPYTER NOTEBOOKS

This is a compilation of Jupyter notebooks that illustrate and implement various concepts in machine learning.
The notebooks are written in Python and utilize the numpy, matplotlib, pandas, seaborn, and sklearn libraries.
These were done as part of the Intro to Machine Learning and Data Mining (CS171) class at the University of California, Riverside.

`KNN Classifier.ipynb` introduces retrieving external data (Iris dataset from the UCI Machine Learning repository) and storing it into a numpy array.
It performs basic analysis and implements a KNN classifier on the data. 

`Linear & Logistic Regression.ipynb` implements linear and logistic regression on the 1970s Boston housing and UCI breast cancer datasets.
These techniques are performed on multiple features and have gradient descent versions.
The data is manipulated to visualize its attributes and the regression's accuracy using matplotlib.

`Neural Network.ipynb` implements a 2-layer neural network to classify digits from the MNIST dataset.
The neural network is trained through the use of loss functions, gradients, and optimizers.
The notebook evaluates the network's accuracy on test data and visualizes classified images.

`K-Means Clustering.ipynb` performs color-based segmentation on an image (located in `images/`) using K-means clustering.
It displays segmented images with a different number of colors using various values of K.
