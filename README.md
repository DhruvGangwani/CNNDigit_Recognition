# CNNDigit_Recognition
Implementation of Custom CNN with Keras Tuner and Transfer Learning

### Implementation

1. Custom CNN Architecture

To build the architecture, layers such as Convolutional, Pooling, and Batch Normalizations were used. Keras Tuner is employed to decide the hyperparamters such as number of neurons, type of activation function, and learning rate. 

2. Transfer Learning

It augments the data before hand to increase the variability and size of data. Thenafter, VGG16 is employed where the lower layers are removed and top layers are considered as "not trainable". In short, only the weights of the top layers of VGG16 are used followed by feed-forward layers for classification.

