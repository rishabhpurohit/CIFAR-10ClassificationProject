# CIFAR-10ClassificationProject



Image classification is a fascinating deep learning project. 

In this project, I built a convolution neural network on a CIFAR-10 dataset. 

First, I did some exploration in our dataset, and then trained my neural network using python and keras.

### Important Dependencies

tkinter is required for GUI creation and launching the application:-

#### !conda install -c anaconda tk


## Dataset

About Image Classification Dataset

CIFAR-10 is a very popular computer vision dataset. This dataset is well studied in many types of deep learning research for object recognition.

This dataset consists of 60,000 images divided into 10 target classes, with each category containing 6000 images of shape 32*32. This dataset contains images of low resolution (32*32), which allows researchers to try new algorithms. The 10 different classes of this dataset are:

 * Airplane
 * Car
 * Bird
 * Cat
 * Deer
 * Dog
 * Frog
 * Horse
 * Ship
 * Truck

CIFAR-10 dataset is already available in the datasets module of Keras. We do not need to download it; we can directly import it from keras.datasets.

## INFO

**model1_cifar_10epoch.h5** is the pretrained model file and must be loaded in GUI CIFAR10 Dataset.py for its working.

**Model_Training_+_exploration.ipynb** is the jupyter notebook in which data exploration is done and model is trained.

run **python GUI CIFAR10 Dataset.py** in a python develpoment environment with exact location of **model1_cifar_10epoch.h5** and all the dependencies and we're good to go!


