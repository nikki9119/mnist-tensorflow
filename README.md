# mnist-tensorflow

MNIST classification is the 'Hello World' of deep learning.

## Model :

The model is a feed forward (Sequential in keras) deep neural network with 2 hidden layers.

**Input layer** - flattening layer which converts the multidimensional input dataset (in our case, 2D dataset (28x28)) into a single dimensional vector.

**Hidden layers** - Dense layers with 128 units (neurons) with 'ReLU' activation. 

**Output layer** - Dense layer with 10 units (since our data has 10 classes) with 'softmax' activation.

## Training the model : 
Model is trained for 3 epochs with adam optimizer and sparse categorical crossentropy to calculate loss.

##### Training set accuracy: 97.7%, Testing set accuracy: 96.92%