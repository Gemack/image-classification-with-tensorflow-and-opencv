## IMAGE RECOGNITION USING CONVOLUTIONAL NEURAL NETWORK (CNN)

[Check out my post on Neuron Network on Hashnode](https://emack.hashnode.dev/understanding-artificial-neuron-network)



This model uses tensorflow to apply deep learning in image classification of product in an Ecommerce store,
this model is trained on the following ecommerce product
### T-SHIRT,
![Screenshot (139)](https://user-images.githubusercontent.com/76667791/190285506-70a231bc-5158-4c16-b99b-20ff2d132a92.png)

### TELEVISION,
![Screenshot (140)](https://user-images.githubusercontent.com/76667791/190285440-2eac1278-1cd6-432d-ad54-965702c2854b.png)


### JEANS


![Screenshot (137)](https://user-images.githubusercontent.com/76667791/190285372-8a2d04f6-28a4-4ae1-95ad-f4d35895ceed.png)
and 
### SOFA.
 ![Screenshot (138)](https://user-images.githubusercontent.com/76667791/190285592-9521df44-c8b2-40a1-944f-0f98edda2629.png)

the python code used in this notebook makes this model very much flexible and can be adjusted for more 
classification.Open CV which is a powerful library in Python, Java and C++ for image and video manipulation was used to load
and perform some minor preprocessing like resizing and grayscaling before feeding images into the network
the model had a 96% accuracy. with 3 layers an input hidden and output layer the input and hidden layer both
have the "relu" activation function, while the output "softmax", for the lost function the
"sparse_categorical_crossentropy" was used instead of the categorical crossentropy because data used was 
not one hot encoded.The popular "adam optimizer" was used as the optimizer function, 
and Accuracy was the evaluation matrix used because our data was even.

# **THIS MODELS IS AS GOOD AS THE DATA USED IN TRAINING IT**.

