# Keras-VGG16-TransferLearning

### Introduction
The aim of this project is to understand ConvNets, use transfer learning to solve (kinda) the challenging problem of image recognition over 2 different datasets - Caltech256[1] and Urban tribes[2]. Caltech256 is a dataset with 256 classes of items, whereas urban tribes is dataset with 11 classes of people like - bikers, goth etc. There are 3-4 files in this repo. Here's a description of what they contain.

* VGG Transfer Learning.ipynb - Shows how to create the transfer learning model, build the dataset from Caltech 256 images and train the model.
* Urban Tribes.ipynb - Same thing as above, but applied on Urban Tribes dataset.
* Caltech256 - Dark knowledge.ipynb - Shows how the temperature parameter can help uncover the knowledge in a network and use it to transfer knowledge.

[1] http://www.vision.caltech.edu/Image_Datasets/Caltech256/
[2] http://www.bmva.org/bmvc/2013/Papers/paper0014/abstract0014.pdf
