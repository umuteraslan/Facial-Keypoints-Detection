# facial_keypoints_detection

In this project, I will be using the dataset from the Kaggle competition 'Facial Keypoints Detection'. 

We are given images of faces as the training data and (x,y) coordinates of 15 keypoints such as eyebrows, eyes, nose etc.. as the labels. We are expected to predict keypoints on the test data in which there are images that don't exist in the training data.

Let's see an image from the train data to get a sense of what we are dealing with:

![An image from training data](/Users/umuteraslan/Desktop/train_face.png)

In order to tackle this problem we will be build a convolutional neural network(CNN) using python3 and tensorflow 2.0.

For the data exploration and manipulation we will use numpy, pandas and matplotlib libraries.

You can check the the requirements.txt file for full list of required libraries.

Upon finishing training our model we will get predictions on the unseen test data as follows:

![An image from test data](/Users/umuteraslan/Desktop/test_face1.png)
![An image from test data](/Users/umuteraslan/Desktop/test_face2.png)



