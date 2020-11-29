# Image-Classifier-using-keras
This is Image classification between Cats and Dogs using CNN

Today, we will create a Image Classifier of our own which can distinguish whether a given pic is of a dog or cat or something else depending upon your fed data. To achieve our goal, we will use one of the famous machine learning algorithms out there which is used for Image Classification i.e. Convolutional Neural Network (or CNN).
So basically, what is CNN – as we know it’s a machine learning algorithm for machines to understand the features of the image with foresight and remember the features to guess whether the name of the new image fed to the machine.

# Dataset
For the dataset we will use the Kaggle dataset of cat-vs-dog divided into training and testing data.

# Build Model

1.Input Layer: It represent input image data. It will reshape image into single diminsion array. Example your image is 64x64 = 4096, it will convert to (4096,1) array.

2.Conv Layer: This layer will extract features from image.

3.Pooling Layer: This layerreduce the spatial volume of input image after convolution.

4.Fully Connected Layer: It connect the network from a layer to another layer

5.Output Layer: It is the predicted values layer.

# Steps involved

Step 1: Now after getting the data set, we need to preprocess the data a bit and provide labels to each of the image given there during training the data set. To do so we can see that name of each image of training data set is either start with “cat” or “dog” so we will use that to our advantage then we use one hot encoder for machine to understand the labels (cat[1, 0] or dog[0, 1]).

Step 2: Import all the required keras packages using which we are going to build our CNN, make sure that every package is installed properly in your machine.

Step 3: Now, we will create an object of the sequential class below:

Step 4: Let us now code the Convolution, pooling operation, Flattening and Dense functions.

Step 5: Now that we have completed building our CNN model, it’s time to compile it.

Step 6: It’s time to fit our CNN to the image dataset that we’ve downloaded. But before we do that, we are going to pre-process the images to prevent over-fitting. Overfitting is when you get a great training accuracy and very poor test accuracy due to overfitting of nodes from one layer to another.

Step 7: Now let’s fit the data to our model!

Step 8:  Making new prediction from our trained model.

# Conclusion

A model that predict between cat and dog is working properly. We used CNN which work fine using TensorFlow backend.
For better and accurate prediction update the training and testing dataset with newer images.
