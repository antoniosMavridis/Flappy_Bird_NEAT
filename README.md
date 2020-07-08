# Flappy_Bird_NEAT
A simple implementation of Flappy Bird using NeuroEvolution of Augmenting Topologies.

## Introduction
NeuroEvolution of Augmenting Topologies (NEAT) is a genetic algorithm for the generation of evolving artificial neural networks (a neuroevolution technique) developed by Ken Stanley in 2002.  It alters both the weighting parameters and structures of networks, attempting to find a balance between the fitness of evolved solutions and their diversity. It is based on applying three key techniques: tracking genes with history markers to allow crossover among topologies, applying speciation (the evolution of species) to preserve innovations, and developing topologies incrementally from simple initial structures ("complexifying").It alters both the weighting parameters and structures of networks, attempting to find a balance between the fitness of evolved solutions and their diversity. It is based on applying three key techniques: tracking genes with history markers to allow crossover among topologies, applying speciation (the evolution of species) to preserve innovations, and developing topologies incrementally from simple initial structures ("complexifying").
It alters both the weighting parameters and structures of networks, attempting to find a balance between the fitness of evolved solutions and their diversity. It is based on applying three key techniques: tracking genes with history markers to allow crossover among topologies, applying speciation (the evolution of species) to preserve innovations, and developing topologies incrementally from simple initial structures ("complexifying").

## Implementation
Our approach is to apply the algorithm using NEAT Python module in order to train it to play Flappy Bird. Our code uses search and optimise technique called genetic algorithm which creates a particular number of random configurations. The best configuration of them is used to create the next generation of neural networks.As we repeat the process, with time, we observe that the performance gets better.

![pygame-window-2020-07-06-14-21-4](https://user-images.githubusercontent.com/49936316/86920530-99bc4700-c132-11ea-8601-01f0dfaf8cd9.gif)

## Instructions
Run flappy_bird.py and watch Neat Algorithm start training itself to play the game of flappy bird.

## Reference
Tim at techwithtim does a great job of teaching all the details of the project. Check it out here : https://www.youtube.com/watch?v=OGHA-elMrxI
