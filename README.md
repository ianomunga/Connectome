# ConnectomeAI
This is an attempt to create comprehensive connectome maps of popular, state-of-the-art Neural Networks
in order to 'unbox' currently black-boxed ANN infrastructures that are NP-hard to elaborately describe.

The following research pathway is currently under experimentation:

• To be able to define an identity tensor **I** such that it's forward propagation throughout the various weighted layers of the 
Neural Network whose connectome is being mapped applied no transformation on the weights of individual nodes themselves.

• Rather, this identity tensor would use self-attention to retain position, absolute value and signage of the weights. Since the 
forward propagation be enabled through the neural networks' activation function, only the statistically significant nodes whose values
contribute to the final output will be traversed by the Self-Attentive Identity Tensor. 

• At the output layer, the Identity Tensor would effectively, in theory, have undergone a functional composition of all the active 
neurons of the Neural Network and in this way, the connectome of the Neural Network can be derived.

The implementations and tests for these sub-pathways will be released weekly on this repository. 


