# Why graphs?
gaphs are a generla language and anlaying entities with relationsa dn interaction. so rather than thinking of th world or a giving fomanin as a set of isolated datapoints,we think of it in terms of networks and relations between these entiities.
This means that we have an undelrying grpah of relations between entities
Modelling the the relational structure of the underlying domain, allows us to build more faitful, accurate models of the underlying phenomena/data.
Networks of particle in physics for example can be represented as graphs. 
The domain is inerently a graph. 
3D shapes is another thing. 
in accelerator physics, we deal with both 3D-shapes (if we discertize the domain) but also, teh particles themselves and their connections using graphs. (however, this owuld be very computaional inepxensive...)



# Dataset 
- Construct data setstochastic gradient descent, after shuffling
# Model
Every Model that you build in Pytoch inherit from nn.model, which is a superclass for every model. 
Makes an easy interface to optimize and run. 
This model has two function. 
- Initilization (defines all the paraameters you use)
- Forwards ( It tells you how to construct teh ocmputation graph form inpt to output)



# GNN PyTorch Concepts

## Introduction
This repository explores concepts related to Graph Neural Networks (GNNs) implemented in PyTorch. It covers fundamental principles, architectural components, and practical examples for building and training GNN models.



## Features
- Implementation of various GNN architectures using PyTorch and PyTorch Geometric.
- Explanation of key concepts such as message passing, node embeddings, and graph convolutions.
- Examples showcasing applications of GNNs in different domains.
- Step-by-step tutorials for building custom GNN models.

## Installation
To set up the environment and install dependencies, run:

```bash
pip install torch torchvision torchaudio torch-geometric
