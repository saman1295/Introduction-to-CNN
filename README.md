# Introduction-to-CNN

A Convolutional Layer is a category of Machine Learning model, namely a type of deep learning model well suited to analyse visual data. They uses principles from linear algebra to extract features and identify patterns within images. 

A CNN uses series of layers each of which detects diffrent features of an input image. Depends on thecompexity of the task, a CNN contains hundreds or thousands of layers to recognise detailed patterns.

A typical CNN architecture contains Convolutional layer, pooling layer and fully connected/dense layer.

![CNN architecture](https://github.com/saman1295/Introduction-to-CNN/blob/main/CNN_architecture.jpeg)


### Convolutional Layer
The main building block of CNN containing set of feature maps/kernels/filters, used to detect features such as edges, colour or textures. The process begins by sliding the kernel across the image's height and width covering a receptive field to learn features in there. 
This transforms the image into a set of feature maps or convolved features, each of which represents presence and intensity of a certain feature at various points in the image.

Each neuron in the kernel will be connected to a receptive field of the same size. these kernels share weights and covers the entire image by sliding across leading to reduced number of parameter to be learned.

### Pooling layer
Similar to convolution layer, this comes with sweeping process. The only difference is it aims to reduce the dimensionality of the input data while retaining critical information, thus improving networks overall efficiency. 

The most common form of poooling is max pooling which retains maximum value in teh selected perceptive field.
 ---Image of max pooling
 ![]()


 * This significantly reduces teh overall number of parameters and enhances the efficiency. 
 * Strenthens modl


CNN is defined by :
- number of feature maps
- receptive field 
- stride