# Manuscript for presentation

## Agenda

I'm name1 and this is name2. We've found that feature selection significantly increases the classification accuracy of breast cancer when using an artificial neural network.

In this presentation we'll first tell you why this study was made.

Then, how we achieved our results, by what methods and proof of thier trustworthiness.

And last what these results conclude and should be put into context.

## About breast cancer

Something about tumours... They can be either benign or malignant, that is fatal or harmless(?)

Today breast cancer is the leading cause of cancer deaths among women. However, early detection increases the chaces of survival and recovery.

The common way of classifying breast cancer mammography screenings. An image as the one here is produced and radiologist examine it to determine if a tumour is benign or malignant.

The process is both time consuming and studies has shown there is a large shortage of radiologists as mammographies are increasingly used.

Other studies has measured the accuracy of radiologist and estimated it to 70%. There has been work made to make this process more efficient.

That is, Computer aided diagnostics


## CAD and Machine Learning

Computer aided diagnostics utilizes machine learning to the classification and assist medial experts in their decision.

The high level concept of machine lerning begins with data. Lets take the example of a mammographic scan. Lots of images are collected and labeled by radiologists to have a key for each datapoint.

A Machine Learning algorithm is trained on this data. It predicts a classification based on an image and by having the key it iteratively can fine tune its parameters to become more accurate.

This trained model can then be used to classify new images and in such a way be utilized as an predictor.

## Feature selection

To explain feature selection let's continue with the example of the image. If the resolution is 256 by 256 the total dimension of the image is 256 squared.

Each pixel represents a dimension of the input to a machine learning model. As some features (in this case pixels) might not contain any useful information they can be considered redundant and don't add to the learning of a model.

Previous studies has shown reducing the amount of features can in cases improve the accuracy and significantly reduce the computation time.

We studied two types of feature selection methods.

### Filter methods

Where all features are ranked based on some condition, such as Entropy. The ranking is made as a preprocessing step and is independent of what Machine Learning classifier are to be used.

### Wrapper methods

Features are evaluated in conjunction with a classifier. That is each feature is tested with an calssifier and are selected based on some condition, such as highest scoring accuracy.

## Why?

Adding these pices of information we naturally asked, can feature selection improve the accuracy of classification of breast cancer?

And in this case one would like to know, in which classification methods is this improvement present?

And the why of our thesis motivated by answering these questions.

## Method

Text...
