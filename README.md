## Ahmed Asini
Here are some projects I worked on.
# Algorithms:
## [Project 1: Wilson algorithm for uniform spanning tree:](https://github.com/AhmedASN/Wilson-Algorithm-for-uniform-spanning-tree)
* 1st part : A theoretical one.Basing on the loop-erased random walk model, We demonstrate the correctness of the algorithm.
* 2nd part : An implementation of the algorithm in Python 
* Results of runing the algorithm on grids of different size:  

![](Images/Grid%20and%20UST.png) 
![](Images/Grid%20and%20UST2.png)

## [Project 2: Metropolis-Hastings Algorithm:](https://github.com/AhmedASN/Metropolis-Hastings-Algorithm)
In statistics, the Metropolis–Hastings algorithm is a Markov chain Monte Carlo (MCMC) method for obtaining a sequence of random samples from a probability distribution from which direct sampling is difficult. This sequence can be used to approximate the distribution (e.g. to generate a histogram) or to compute an integral (e.g. an expected value). Metropolis–Hastings and other MCMC algorithms are generally used for sampling from multi-dimensional distributions, especially when the number of dimensions is high. 
I Applied the algorithm in two situations ( the global version and the local one ) to show how the results are not so satisfying in some cases ( here the presence of wells ). As you can see in the comparaison below, the difference in convergence speed is huge. For the implementation (in Python )and more details [click here](https://github.com/AhmedASN/Metropolis-Hastings-Algorithm).

![](Metropolis-Hastings%20Algorithm%20Images/glob%20and%20loc.png)

# Data Science:
## [Project 1: Hand written digits recognition using CNN-keras:](https://github.com/AhmedASN/Hand-written-digits-recognition-CNN-keras-)
MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. We use two convolutional neural networks, one is based on Conv2D and the other on SeparableConv2D from Keras,  to recognize hand written digits.

![Samples](Images2/samples.png)

The neural networks will be training on a data set with the following property :
![Number of digit classes](Images2/Number%20of%20digit%20classes.png)

CNN (Convolutional Neural Network) based on Conv2D achieved ***99.8%*** in accuracy while CNN based on SeparableConv2D achieved ***98.5%*** .
