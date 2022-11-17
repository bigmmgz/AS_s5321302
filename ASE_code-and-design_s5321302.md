# Object Recognition


## Abstract
The input image is used to recognize the features in the image using the CNN architecture system and to classify the objects in the image.


## Detailed Description
Image data consisting of multiple channels is fed into a convolutional neural network, and after multiple convolution, pooling and activation, the data features are extracted. The output is then passed through a fully connected layer to complete the forward propagation process. The parameters are then updated in the back propagation by calculating the loss between the predicted value and the true value. This step is repeated until a model with better recognition results is trained.


### Datasets
The CIFAR-10 dataset contains 60,000 colour images, divided into 10 categories. Of these, 50,000 are training images and the remaining 10,000 are test images.

https://www.cs.toronto.edu/~kriz/cifar.html


### Arcitecture Proposal
1. Input training samples and process the data.
2. Construct convolutional neural network.
3. Set the optimizer and calculate the loss function.
4. Update parameters.
5. Evaluate the model.


## References
[1]Learning Multiple Layers of Features from Tiny Images，Alex Krizhevsky，2009
[2]Ming Liang, Xiaolin Hu; Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2015, pp. 3367-3375
[3]R. L. Galvez, A. A. Bandala, E. P. Dadios, R. R. P. Vicerra and J. M. Z. Maningo, "Object Detection Using Convolutional Neural Networks," TENCON 2018 - 2018 IEEE Region 10 Conference, 2018, pp. 2023-2027, doi: 10.1109/TENCON.2018.8650517.