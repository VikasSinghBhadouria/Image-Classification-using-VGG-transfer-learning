# Image-Classification-using-VGG-transfer-learning
Image classifier using VGG transfer learning and using our own classifier as head .


We are implementing transfer learning using Keras  and VGG model.
The famous VGG  network is  trained on millions of images for 1000 classes. 
We are using it's weights in our network.
Our own classifier will be used in the last layer as head to classify between cat and Dog .
We have little data just 2000 images for training and 400 for testing purpose .
So, we are using image augmentation to increase the training data .

If you are interested in creating a CNN from sctrach ,
refer : https://github.com/VikasSinghBhadouria/Classification-of-Cat-and-Dog-CNN-with-image-augmentation

 By using our own CNN  only , we get the accuracy of 77-78 percent.
 
 However , using transfer learning , we achived the accuracy of 90-91 percent .
 
 

It uses data that can be downloaded at: https://www.kaggle.com/c/dogs-vs-cats/data In our setup, we:

created a data/ folder
created train/ and validation/ subfolders inside data/
created cats/ and dogs/ subfolders inside train/ and validation/ We are using mini-data as that will be enough for our purpose . So that we have 1000 training examples for each class, and 450 validation examples for both class. In summary, this is our directory structure:
data/
    train/
        dogs/
            dog001.jpg
            dog002.jpg
            ...
        cats/
            cat001.jpg
            cat002.jpg
            ...
    validation/
        dogs/
            dog001.jpg
            dog002.jpg
            ...
        cats/
            cat001.jpg
            cat002.jpg
            ...
'''

