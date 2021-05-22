# Rice-Leaf-Deases-Detection

## In developing countries, farming land can be much larger and farmers cannot observe each and every plant, every day. Farmers are unaware of non-native diseases. 
## The model will help them in detecting which of the diseases the rice leaf has. 
## To perform Rice diseases prediction, some basic knowledge on neural network, CNN and image processing is needed.


# CNN Architecture 

# The model’s architecture consists of two main parts, five convolutional blocks and two fully connected neural network layer.
# The inputs to this model are 220x220 images.
# We are using five convolutional layers with one using 32 (3x3) filter, two using 64 (3x3) filter and the other two using 128 (3x3) filter and ReLU as an activation function followed by max pooling layer of pool and dropout.
# The output of convolutional layer is flattened and sent to first fully connected layer of 1024 neurons followed by ReLU activation, Batch Normalization and Dropout and then to 3 neuron layer with softmax activation function which will give us our output.
