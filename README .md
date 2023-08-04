
## Multi-Layer Perceptron

This project focuses on feature extraction of CIFAR images using ResNet18 model. The goal is to extract features of images in the CIFAR dataset and use these features to train a classifier.

## Feature Extraction
The code for feature extraction can be found in the feature_extractor.py file. The feature extraction function of the BBResNet18 class is used to generate feature vectors. The function expects each image to be a numpy.ndarray of dtype numpy.float32 and shape [None, 3, 224, 224], where None represents a variable size. The function returns a numpy.ndarray of dtype numpy.float32 and shape [None, 512].


## Set Up The Project File





	pip install pandas
	pip install numpy
	pip install matplotlib
	pip install sklearn
    pip install torch
    pip install torchvision


Download the CIFAR dataset from the link provided above and extract it to the same directory as the code:
	https://www.cs.toronto.edu/~kriz/cifar.html

## Feature Extraction
The code for feature extraction can be found in the feature_extractor.py file. The feature extraction function of the BBResNet18 class is used to generate feature vectors. The function expects each image to be a numpy.ndarray of dtype numpy.float32 and shape [None, 3, 224, 224], where None represents a variable size. The function returns a numpy.ndarray of dtype numpy.float32 and shape [None, 512].




### For Feature Extraction in Pickle file 

Run the code by executing the cifar.ipynb file.

You can also download the pickles files that will be created after running cifar.ipynb file and used in model.ipynb file to run model:    https://iitk-my.sharepoint.com/personal/kartickv22_iitk_ac_in/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fkartickv22%5Fiitk%5Fac%5Fin%2FDocuments%2FCourse%2FDeep%20Learninig&ga=1

### To Run MLP Model

Run the code by executing the model.ipynb file.

