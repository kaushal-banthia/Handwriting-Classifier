# Predicting-if-its-my-handrwiting
This model uses Neural Networks and Random Forests to determine if the input photo is my handwriting or not. 

All the data used has been taking by my phone and hence needed some preprocessing and data augmentation.
Neural networks don't seem to work well as they give some 60% accuracy at max on the train data while Random Forests give 100% on train and 80% on test data.

Model_for_prediction.ipynb : This is main jupyter notebook file written in Python 3

model.txt : This text file contains one of my saved models for Random Forests

my.jpg, my1.jpg, my2.jpg: Test pictures that are my handwriting (You can't find them anywhere else ;)

not_my.jpg, not_my1.jpg : Test pictures that are not my handwriting (You can try some for your own)

photos.txt : Contains the address for all the images that are my handwriting

not_photos.txt : Contains the address for all the images that are not my handwriting
