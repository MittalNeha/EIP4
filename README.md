Score
[0.03241152514670962, 0.9937]

Write your own definitions for:

<b>Convolution</b>: Convolution is used to filter out features in the input. It keeps amplifying required features and the features which do not pass through the filter keep deteriorating.

<b>Filters/Kernels</b>: This is the matrix that is convolved with the input to perform convolution.

<b>Epochs</b>: One complete cycle of training involves forward and back propagation. When this full cycle is performed for all samples in the training set, its called one epoch.

<b>1x1 Convolution</b>: This is used to maintain the information in the input by averaging the channel pixels. It doesn't look around the pixels on the same plane.

<b>3x3 Convolution</b>: In this a 3 by 3 filter is convolved with the input. Hence it looks at the neighborhood of each pixel.

<b>Feature Maps</b>: This is what comes out of each layer after convolution + activation.

<b>Activation Function</b>: Used to introduce non-linearity in the network. Withour non-linearlity, its all just a linear equation.

<b>Receptive Field</b>: It is the portion of image that is being looked at once. 3x3 convolution has a receptive field of 3 because its looking at 3x3 pixels at a time
