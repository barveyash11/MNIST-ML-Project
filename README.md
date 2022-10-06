# MNIST-ML-Project
Hello folks,

As the name suggests, this is an MNIST Project. For starters, MNIST is basically handwriting recognition for digits. 
As the input, you have pass in an image of a digit, and the model will detect which digit it is. 

The neural networks consists of 3 layers after flattening the input. There are 2 RELU activation layers each consisting of 50 units.
Finally there is a sigmoid activation unit consisting of 10 units for each of the 10 digits.
I am also working on making the same model using CNN's which would improve the accuracy. However, for such small images, even a simple NN is good enough.
I have used the 'adam' optimiser and the 'sparse_categorical_crossentropy' as the loss function.

The output that you get from the neural-net is a list of 10 numbers, which are the probabilities that the image is a particular digit.
For example, the first number in the output list is the probability of the image being a 0, the second number is the probability of the image being a 1, and so on,
Then, we take the maximum value from the output list which indicates the prediction of the model.
