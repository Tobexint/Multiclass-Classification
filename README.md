# Summary
In this lesson, we'll work with the full wildlife dataset, which has eight classes. This is more than the network in the previous notebook can handle. Here we'll build and train a more complicated neural network, called a Convolutional Neural Network, that is meant for working with images. We'll use this network to get the predictions we need for the competition at DrivenData.org.

## Objectives
- Read in data with multiple classes
- Normalize our data to improve performance
- Create a Convolutional Neural Network that works well with images
- Train that network to do multiclass classification
- Reformat the network predictions to complete the competition

## New Terms
- Multiclass
- Normalize
- Convolution
- Max pooling

## The Competition
As a reminder, the data we're working with came from a competition at DrivenData.org. The goal of the competition is to build a model that takes an image and classifies what animal is in it. There are seven animals, plus a 'blank' where no animal is present in the image.
We're almost ready for the competition now. We need to expand our network to handle all eight categories. We could do this with the simple network we've already built, but it would perform poorly. Instead, we're going to build a more complex network that's meant for working with images. This is called a Convolutional Neural Network, and involves arranging the neurons in a different pattern.
Once we have built and trained this network, its output will be what the competition is looking for. We'll get our predictions and save them into the requested format.
