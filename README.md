# Facial Keypoint Detection

### Problem Statement
Detecting keypoints in a given image is getting more and more important in the era of deep learning and computer vision. We see real world  applications of this topic mainly in some face recognition and driverless car projects. Our task is predicting the coordinates of predefined keypoints on a given image.

### Dataset and Project Description 
In this project, I will be using the dataset from the Kaggle competition 'Facial Keypoints Detection'. 

Dataset can be downloaded from: https://www.kaggle.com/c/facial-keypoints-detection/data

We are given images of faces as the training data(train.csv) and (x,y) coordinates of 15 keypoints such as eyebrows, eyes, nose etc.. as the labels(train.csv) in a csv format. We are expected to predict keypoints on the test data(test.csv) in which there are images that don't exist in the training data.

Let's see an image from the train data to get a sense of what we are dealing with:

![An image from training data](/images/train_face.png)

### Solution Approach
In order to tackle this problem we will build a convolutional neural network(CNN) using python3 and tensorflow 2.0.

For the data exploration and manipulation we will use numpy, pandas and matplotlib libraries.

You can check the the requirements.txt file for full list of required libraries.

Upon finishing training our model we will get predictions on the unseen test data as follows:

![An image from test data](/images/test_face.png)

![An image from test data](/images/test_face2.png)

### Takeaways
There are some practical takeaways of this project that can be transferred to other projects:

* The project is built on google colab notebook which allows us to use tensorflow2.0-gpu in the cloud environment. This is a great way of building deep neural network projects since it allows us to utilise free gpu provided by Google which is usually a lot faster than most laptops and desktops. 
* In order to achieve decent computer vision results, we don't have to build very deep neural networks. For tasks similar to this project, a very similar model would most probably achieve decent results.
* CNNs are very powerful when it comes to detecting different patterns in image files
