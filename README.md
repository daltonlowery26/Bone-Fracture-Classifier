# Bone Fracture Classification

## -- Project Status: Active

## Project Intro/Objective

Using data soured from various medical repositiories, my goal was to build a CNN to classify if something is a fracture or not. The goal was to be able to identify any examples of a bone fracture, not only ones in a certian reigon of focus.

## Project Description

Using Pytorch and openly found datasets on the internet my goal was to build a model to classify if something is a bone fracture or not. I used a CNN model of the structure (Conv, LRELU, BatchNorm, Conv, LRELU, Batchnorm, MaxPool)x3 ADPAVGPOOl, Fully Connected Network. I choose to build a custom structure not because I thought it would preform better, but because I wanted to better learn how CNNs work and the design choices that had to be made. If I was to build a model for production, I would use transfer learning and a ResNet architecture. I chose to do all the image preprocessing before feeding the images into the model to create more efficent training enviorment. I had a dataset of around 6k original images and used medically relevant transforms to end up with a dataset of around 36k images. My model was limited by this lack of data, as well as mislabeled fracture data. I then uploaded the image dataset to google drive and did all the training on colab because of the acesses to devices with increase power and GPU RAM.

## Contact

*Please email with any questions!
