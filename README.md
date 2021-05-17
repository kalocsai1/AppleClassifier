# AppleClassifier

This is a demo project to show the use of various Deep Learning techniques for the classification of 13 different kinds of apples. 

First, we use transfer learning by modifying MobileNet version 1. The first 23 layers of MobileNet are kept frozen. The rest of the layers are replaced by a single fully connected output layer. The Python code for this version is in the 'AppleClassifier.ipynb' jupyter notebook.

Second, we build our own model by adding layers via the Keras API. The Python code for this version is in the 'AppleClassifier2.ipynb' jupyter notebook.

Both models are only run for 2 epochs because they achieve perfect performance on the validation and test data rather fast. 

The data for this demo comes from the 'Fruits 360' dataset by Miahi Olteran available on kaggle at: 
https://www.kaggle.com/moltean/fruits

All the data used here is contained in the 'data.zip' file.

Dataset Properties:

Total number of images: 8,279

Training set size: 7,044 images

Validation set size: 1,040 images

Test set size: 195 images

Number of classes: 13 types of apple

Image size: 100x100 pixels
