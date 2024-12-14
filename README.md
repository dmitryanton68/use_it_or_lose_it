# __Weight regularization in spiking neural networks__
The code illustrates the result reported at the [XXXII All-Russian workshop 'Neuroinformatics, its applications and data analysis' at Akademgorodok, Krasnoyarsk, Russia.](https://www.researchgate.net/publication/384485253_Weight_regularization_in_spiking_neural_networks)

### ARTICLE:
Antonov D.I., Sukhov S.V. "Weight regularization in spiking neural networks." Proceedings of XXXII All-Russian workshop 'Neuroinformatics, its applications and data analysis'. Krasnoyarsk. Russia. 2024. pp.10-17. 
***
Abstract:    
The desired result of any learning of an artificial neural network is the ability to generalize knowledge to solve new problems. However, mindless minimization of the loss function may result in overfitting of the model. Overfitting is a result of training taking into account both essential and insignificant features, noise. Regularization methods are intended to minimize the influence of random noise and to identify regular features. There are many regularization methods for 2nd generation artificial neural networks (L1 regularization, L2 regularization, dropout, etc.). But these conventional regularization methods are not suitable for spiking neural networks. This paper presents a new technique for regularizing weights in spiking neural networks.    
***
We propose the weight regularization method for SNNs based on the biological ‘use it or lose it’ concept.       
if a synaptic connection is not used in a brain, it is pruned. To ensure the pruning of unnecessary weight in SNNs, all the weights become time-dependent.   
To test our regularization concept, we perform a series of experiments with SNNs. In experiments, the SNN is trained with the aim of classification of MNIST images of handwritten digits. The purpose of the experiments was to compare the SNN output activity with or without weight regularization. The SNN in all the experiments uses the leaky integrate-and-fire neurons with an adaptive threshold for excitatory neurons.    
[Used architecture of SNN](https://github.com/dmitryanton68/learning_rule_STDP_all-LTD/blob/main/SNN_architecture.jpg) 
