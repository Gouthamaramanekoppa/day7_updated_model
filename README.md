# day7_updated_model
Updated model by adding Flatten layer to reshape input images properly before training.

The focus was on modifying the neural network architecture to properly handle image input data. The MNIST dataset consists of images with dimensions 28 × 28 pixels. However, dense (fully connected) layers in a neural network expect input data in a one-dimensional format.

To solve this, a Flatten layer was introduced at the beginning of the model. The Flatten layer converts the 2D image matrix (28 × 28) into a 1D vector (784 values). This transformation does not change the data itself; it only reshapes the structure so it can be processed by dense layers.
