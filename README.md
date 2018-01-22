# Handwritten_Digit_Recognition
The basic Hello World program of ML.

Dataset-MNIST dataset 60,000 training images,10,000 test images.

2 models were tested -


### Simpler CNN

* Conv2D layer with 32/*5/*5 filters ,relu activation function.
* Maxpooling layer of 2/*2.
* Regularization using Dropout.
* Flatten layer.
* FC layer with 128 neurons,relu activation functions.
* Output layer for 10 classes and softmax activation function.

### Larger CNN

* Conv2D layer with 30/*5/*5 filters ,relu activation function.
* Pooling layer of 2/*2
* Conv layer with 15/*3/*3.
* Dropout layer with 20% probability.
* Flatten layer.
* FC layer with 128 neurons and relu activation function.
* Output layer for 10 classes and softmax activation function.

Both were trained on AWS EC2 instances on gpu-g2.2x large/
