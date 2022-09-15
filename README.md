## IMAGE RECOGNITION USING CONVOLUTIONAL NEURAL NETWORK (CNN)

My post on Neural network on hashnode.

This model uses tensorflow to apply deep learning in image classification of product in an Ecommerce store,
this model is trained on the following ecommerce product
### T-SHIRT, 
### TELEVISION,
### JEANS and 
### SOFA.
 
the pythoncode used in this notebook makes this model very much flexible and can be adjusted for more 
classification.Open CV which is a powerful library in Python, Java and C++ for image and video manipulation was used to load
and perform some minor preprocessing like resizing and grayscaling before feeding images into the network
the model had a 96% accuracy. with 3 layers an input hidden and output layer the input and hidden layer both
have the "relu" activation function, while the output "softmax", for the lost function the
"sparse_categorical_crossentropy" was used instead of the categorical crossentropy because data used was 
not one hot encoded.The popular "adam optimizer" was used as the optimizer function, 
and Accuracy was the evaluation matrix used because our data was even.
"# image-classification-with-tensorflow-and-opencv" 
