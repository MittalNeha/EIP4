Score 0.9921

Write your own definitions for:
Convolution: Convolution is used to filter out features in the input. It keeps amplifying required features and the features which do not pass through the filter keep deteriorating.
Filters/Kernels: This is the matrix that is convolved with the input to perform convolution.
Epochs: One complete cycle of training involves forward and back propagation. When this full cycle is performed for all samples in the training set, its called one epoch.
1x1 Convolution: This is used to maintain the information in the input by averaging the channel pixels. It doesn't look around the pixels on the same plane.
3x3 Convolution: In this a 3 by 3 filter is convolved with the input. Hence it looks at the neighborhood of each pixel.
Feature Maps: This is what comes out of each layer after convolution + activation. 
Activation Function: Used to introduce non-linearity in the network. Withour non-linearlity, its all just a linear equation.
Receptive Field: It is the portion of image that is being looked at once. 3x3 convolution has a receptive field of 3 because its looking at 3x3 pixels at a time
