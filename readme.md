## Machine Learning Capstone Project - Udacity MLND(iWildCam 2019 - FGVC6)


Wild cams are used to collect large quantities of image data automatically. These wild cams / camera traps are used by the biologists all over the world to monitor the biodiversity and population density of animal species. The recent strides towards automating the species classification challenge in wild cams when expanded the scope, an interesting problem is encountered i.e., how do you classify a species in a new region that you may not have seen in previous training data?

To classify the species correctly, a machine learning algorithm is used. The model is built in such a way that it is able to produce a good accuracy in classifying the image. I would consider implementing a convolutional neural network model than the multilayer perceptron as CNN works better in image classification and recognition. A pre-trained network is used to train the model.
So, while predicting the category of the species, the following strategy can be implemented.
1. Initially, the train, test data and images are loaded into the system. Preprocessing is done to reduce the image size as well as data cleaning.
2. Now, the saved reduced images are loaded and then scaled.
3. A CNN classifier model is created and then is trained.
4. A pretrained Densenet model is used in Keras.
5. A model check point function is created to calculate the accuracy.
6. The model is now validated by plotting the test vs train.


1.Following are the file descriptions and URL’s from which the data can be obtained :
```
• train_images.zip - a list containing all the training images.
• test_images.zip - a list containg all the test images.
• sample_submission.csv - a sample submission file in the correct format
• train.csv - It contains file path name and label
• test.csv - It contains test file and its label

https://www.kaggle.com/c/iwildcam-2019-fgvc6/data

```


2.Following are the details of Software environments with version details :
```
• Python 3.6.0 :: Anaconda 4.3.1 (64-bit)
• Tensorflow 1.1.0
• Keras 2.0.4
```
