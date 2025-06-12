# GPTCoreConceptImp
Implementation of Attention all you need paper

Here I am trying to implement encoder and decoder as written in Attention all you need paper

Implementation of attention function and using softmax function

# DeepLearning

Before implementing LLM we just need to understand few concepts in Deep Learning

convolutional neural network is good for image recognation

Long short term memory network is good for speech recognation


neuron is a thing that holds a number from 0-1 and number inside neuron is activation  for example if you have a 28*28 pixal image then it has 784 neuron connected and has grey scale value from 0(dull) to 1(brightest)

These 784 makes it as first layer of network to find number in the picture using neural network and output layer has 0-9 digits with corresponding activation number and it has some hidden layers which help to detect actual output value based on input and will get brightest in output layer

For example hidden layer has 16 neurons  and consider them as weight and we need to multiply with all values of 784 neurons activation numbers and need to have a bias to set a standard value..so for each hidden layer neuron has an bias and we need to add them and we use sigmoid function as we need to get value between 0-1 for this neural network

Sigma(sum(w*a+bias)) for all weights and activations

Basically these neural networks are trained to image recognations so we need to know how they trian them..

We need to find cost function and gradient decent of that cost functions and negative of gradient decent give you actual value which is local minimum to determine the exact value

Using back propagation we get gradient decent of the network

lets start with implementation and learn concept while implementing..